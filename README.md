# Maritime Hackathon
---

## Usage
Open a new folder in your terminal
```pwsh
mkdir maritime_hackathon
cd maritime_hackathon
```

Clone the repository
```pwsh
git clone https://github.com/stupidbutsmart/pookie
cd pookie
```

Pull from main branch
```pwsh
git checkout main
git pull origin main
```

Create a new branch for what you are working on
```pwsh
git checkout -b feature/<name of feature>
```

**When you create a new feature and want to commit**
```pwsh
git checkout feature/<name of feature>
git add .
git commit -m '<commit message>'
git push origin feature/<name of feature>
```

Go to repository to send a **Pull Request** _(PR)_

**How to sync with main**  
When changes are made in main, run the following code
```pwsh
git pull origin main
```

---

## Rulesets
- All features are to be written in `.py` files
- The main `index.ipynb` file will be a notebook to show our analysis
- `index.ipynb` will import functions written inside of other `.py` files
- **ALL** function , variable names are to follow `snake_case`
- **ALL** classes are to follow `PascalCase`
- **ALL** class or object **constant attributes** are to follow `snake_case` with a trailing underscore `_`
- **ALL** identifiers are to be **verbose and meaningful** (no skibidi sigma)
