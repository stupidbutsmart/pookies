# Maritime Hackathon
---

### Usage
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
