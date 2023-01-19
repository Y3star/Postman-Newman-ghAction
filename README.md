# Postman + newman + github actions 
**Setup**

**Download git repository and use install node modules:**
```console
git clone {repository URL}
```
**Open folder with your project and use command:**
```console
npm install
```
**Run command in Bash console to start local server:**
```console
npm run tern-on-api
```
**Command to run petstore.collection.json with html report.** **You can view html report in folder newman in any browser**
```console
newman run petstore.collection.json -r htmlextra
```
**Command to run petstore.collection.json with allure report**
```console
newman run petstore.collection.json -r allure
```
**To generate allure report**
```console
allure generate allure-results --clean -o allure-report
```
**To view allure in local virtual server**
```console
allure serve allure-results
```
**How look like allure report view report**
![](https://i.imgur.com/2fdGqhQ.png)
