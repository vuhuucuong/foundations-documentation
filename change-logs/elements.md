---
description: >-
  Below you will find a listing of the recent changes we have made to the
  Elements package. This includes details of any bugs that have been fixed or
  features/enhancements that have been added.
---

# Elements
### elements_v1.0.41_released - 2020-03-24
  
Release: cognito-auth_v2.1.0
Rollback: cognito-auth_v2.0.19
Changes:
commit | author |description
  
- 52b09559a0cd10b2c77f20a1636bb39de9c20e60 | Pham Hai Duong <duongph@reapit.com> | fix: #568 fix react scaffolder bug (#695)fix: #568 fix react scaffolder bug
- 0fb24fbe92ca4b2c71264b28a9e3cc2bf9102627 | Pham Hai Duong <duongph@reapit.com> | fix: #568 react scaffold after migration to config.json (#693)Changes- Add export default app.tsx- Change index.tsx to remove import index.scss
- 3f973622334cce228105865b66e24028673349e1 | Pham Hai Duong <duongph@reapit.com> | chore: #629 migrate to config of json (#673)Changes- Migrate for web-components- Migrate for smb- Migrate for cognito custom mail lambda- Migrate for cognito auth
- e32f8fa0809b80dd153a548b13ab77ac0d6c43ed | Pham Hai Duong <duongph@reapit.com> | chore: #629 migrate config of apps to config.json (#644)chore: #629 migrate config of apps to config.json (#644)
- a8238dc3ea76f1468949895f8732e322883513b0 | Cuong Vu <cuongvh@reapit.com> | fix: #597 updates to desktop interaction for cloud apps (#646)* fix: #597 updates to desktop interaction for cloud apps
- 241590e07280434cd0bf8f6ab65a3e7e7d322279 | Cuong Vu <cuongvh@reapit.com> | chore: #473 GraphQL Server Refactor (#548)* chore: #473 refactor graphql server
- cfa5635aa0ea5d1c9ee4da83c548213eef47c0f6 | Cuong Vu <cuongvh@reapit.com> | fix: fix failing pipeline (#521)* fix: reconstruct packages depedencies, fix webpack.sass not throw errors* fix: add todo comment, remove unused config, add sentry_log_level* fix: remove SENTRY_LOG_LEVELS env, add to sentry webpack plugin instead
- 8e0080b8b62a04db3ea810bfad77daa03db7fa0c | NghiaPham <nghiapn@dwarvesv.com> | chore: #368 Add resolver for graphql server to call appointment services (#389)
- c6a4c531dca8e4b6f2b1dff6669c73dba1f7c9bc | Pham Hai Duong <tanphamhaiduong@gmail.com> | chore: #128 remove redundant and restructure dependencies (#451)* chore: #128 remove redundant and restructure dependencies* chore: resolve all warning on build console* chore: resolve warning peer dependencies for install by yarn* fix: resolve package cognito-auth in cognito package* chore: remove query-string dependency
- 64d096cbb85ef4bc98f86ad6964e8c4527579479 | Cuong Vu <vuhuucuong1310@gmail.com> | chore: #125 improve webpack bundling performance (#445)* chore: #125 (POC) improve webpack bundling performance locally* chore: #125 add mode for webpack dev* chore: #125 resolve conflicts* chore: #125 graphql-server add tsconfig path to cognito-auth* chore: #125 update pullrequest pipeline to include cache build* chore: #125 update pullrequest pipeline to include marketplace cache* chore: #125 correct cache keys* chore: #125 first build test (expected to take long time)* chore: #125 concurrently build in elements* chore: #125 second test* chore: #125 remove duplicated --parallel flag* chore: #125 ignore .temp folder* chore: #125 remove babel-loader built-in cache* chore: #125 finish pipeline* chore: #125 test pipeline* chore: #125 readd sass temp* chore: #125 add jest cache* chore: #125 refactor & finish* chore: #125 finish both ci/local cache settings* chore: #125 fix hooks not run* chore: #125 fix echo & cp not working in windows

approver: @willmcvay
monitor: https://sentry.io/organizations/reapit-ltd/projects/
    
### elements_v1.0.20 - 2020-03-24
  
Release: cognito-auth_v2.1.0
Rollback: cognito-auth_v2.0.19
Changes:
commit | author |description
  
- 52b09559a0cd10b2c77f20a1636bb39de9c20e60 | Pham Hai Duong <duongph@reapit.com> | fix: #568 fix react scaffolder bug (#695)fix: #568 fix react scaffolder bug
- 0fb24fbe92ca4b2c71264b28a9e3cc2bf9102627 | Pham Hai Duong <duongph@reapit.com> | fix: #568 react scaffold after migration to config.json (#693)Changes- Add export default app.tsx- Change index.tsx to remove import index.scss
- 3f973622334cce228105865b66e24028673349e1 | Pham Hai Duong <duongph@reapit.com> | chore: #629 migrate to config of json (#673)Changes- Migrate for web-components- Migrate for smb- Migrate for cognito custom mail lambda- Migrate for cognito auth
- e32f8fa0809b80dd153a548b13ab77ac0d6c43ed | Pham Hai Duong <duongph@reapit.com> | chore: #629 migrate config of apps to config.json (#644)chore: #629 migrate config of apps to config.json (#644)
- a8238dc3ea76f1468949895f8732e322883513b0 | Cuong Vu <cuongvh@reapit.com> | fix: #597 updates to desktop interaction for cloud apps (#646)* fix: #597 updates to desktop interaction for cloud apps
- 241590e07280434cd0bf8f6ab65a3e7e7d322279 | Cuong Vu <cuongvh@reapit.com> | chore: #473 GraphQL Server Refactor (#548)* chore: #473 refactor graphql server
- cfa5635aa0ea5d1c9ee4da83c548213eef47c0f6 | Cuong Vu <cuongvh@reapit.com> | fix: fix failing pipeline (#521)* fix: reconstruct packages depedencies, fix webpack.sass not throw errors* fix: add todo comment, remove unused config, add sentry_log_level* fix: remove SENTRY_LOG_LEVELS env, add to sentry webpack plugin instead
- 8e0080b8b62a04db3ea810bfad77daa03db7fa0c | NghiaPham <nghiapn@dwarvesv.com> | chore: #368 Add resolver for graphql server to call appointment services (#389)
- c6a4c531dca8e4b6f2b1dff6669c73dba1f7c9bc | Pham Hai Duong <tanphamhaiduong@gmail.com> | chore: #128 remove redundant and restructure dependencies (#451)* chore: #128 remove redundant and restructure dependencies* chore: resolve all warning on build console* chore: resolve warning peer dependencies for install by yarn* fix: resolve package cognito-auth in cognito package* chore: remove query-string dependency
- 64d096cbb85ef4bc98f86ad6964e8c4527579479 | Cuong Vu <vuhuucuong1310@gmail.com> | chore: #125 improve webpack bundling performance (#445)* chore: #125 (POC) improve webpack bundling performance locally* chore: #125 add mode for webpack dev* chore: #125 resolve conflicts* chore: #125 graphql-server add tsconfig path to cognito-auth* chore: #125 update pullrequest pipeline to include cache build* chore: #125 update pullrequest pipeline to include marketplace cache* chore: #125 correct cache keys* chore: #125 first build test (expected to take long time)* chore: #125 concurrently build in elements* chore: #125 second test* chore: #125 remove duplicated --parallel flag* chore: #125 ignore .temp folder* chore: #125 remove babel-loader built-in cache* chore: #125 finish pipeline* chore: #125 test pipeline* chore: #125 readd sass temp* chore: #125 add jest cache* chore: #125 refactor & finish* chore: #125 finish both ci/local cache settings* chore: #125 fix hooks not run* chore: #125 fix echo & cp not working in windows

approver: @willmcvay
monitor: https://sentry.io/organizations/reapit-ltd/projects/
    

