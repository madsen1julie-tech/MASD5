Start på main:
git switch main

Pull så up to date
git pull

Download de rigtige pakker i envirmoment #kun første gang
python3 -m venv .venv
source .venv/bin/activate ## det er på mac
python -m pip install -r requirements.txt

Og lave en gitigorne #også kun første gang
touch .gitignore
put enviroment derind
echo ".venv/" >> .gitignore

Og for at lave en kernel til ipynb #tror også kun en gang
python -m pip install ipykernel pandas openpyxl jupyter
python -m pip list
python -m ipykernel install --user --name=masd5

Skift til min branch
git switch Julie

Hvis jeg vil have nyeste ændring fra main over på Julie
git merge main

Arbejd arbejd arbejd

Gem på computer med cmd + s

gem på repository ved at:
se hvad der er ugemt
git status

hvis du vil gemme alle ændringer
git add .

eller kun en fil f.eks.
git add readme.txt

commit til repository
git commit -m "en lille kommentar"

og så push
git push

og hvis mit lort virker og jeg vil push til main
git switch main
git pull
git merge Julie
git push