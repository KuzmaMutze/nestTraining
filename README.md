npm set-script prepare "husky install" && yarn prepare

npx husky add .husky/pre-commit "yarn lint-staged"