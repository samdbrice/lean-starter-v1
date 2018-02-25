# L(inux)E(xpress)A(ngular)N(est)
## LEAN Stack - TypeScript Starter

Implementation of [LEAN Stack](https://medium.com/@sbrice/lean-stack-lamp-stack-reborn-dcbee8f04320) using the [Nest](https://github.com/nestjs/typescript-starter) and [Angular](https://github.com/sbrice/angular-starter) starter packs. Ready for Heroku deployment.

## Install
```bash
npm run install
```

## Develop
```bash
npm run start:dev
```

### Deploy
```
heroku create
heroku config:set NPM_CONFIG_PRODUCTION=false
git push heroku master
heroku open
```

enjoy - [sbrice](https://medium.com/@sbrice)