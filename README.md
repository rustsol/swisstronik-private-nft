
## Steps

### 1. Clone Repository

```bash
git clone https://github.com/rustsol/swisstronik-private-nft.git
```
```bash
cd swisstronik-private-nft
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file
```bash
PRIVATE_KEY="your private key"
```

### 5. Compile Smart Contract

```bash
npm run compile
```

### 6. Deploy Smart Contract

```bash
npm run deploy
```

### 7. Mint Token

```bash
npm run mint
```

### 8. Finsihed

- Open the deployed-adddress.ts (location in utils folder)
- Copy the address and paste the address into testnet dashboard
- push this project to your github and paste your repository link in testnet dashboard
  
 #how to push ? 
```bash
git init
```
```bash
git add .
```
```bash
git remote set-url origin your_repo_link
```
```bash
git branch -M main
```
```bash
git push -u origin main
```

