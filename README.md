# Start Develop

### 1.Install node js >= 18
use `fnm`

```shell
# Install (nodejs version manager)
brew install fnm

# Add fnm setting in ~/.zshrc
eval "$(fnm env --use-on-cd --shell zsh)"

# Install nodejs over 18.x.x
fnm install 20.17.0

# Install yarn
npm install --global yarn
```

### 2. Install dependency
```shell
yarn install
yarn global add @nestjs/cli
```

### 3. Add secret file
```shell
touch .env
```
`MICROSOFT_TEAMS_WEBHOOK_URL` 을 채워주세요

### 4. Start project in dev mode
```shell
yarn run start:dev
```




