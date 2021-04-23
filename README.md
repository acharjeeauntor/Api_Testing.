# Api_Testing.
This repo contains Dummy Customer Api Testing with generate a report using newman.

#### Collection and Environment are present collection folder
------------------
### To install packages:
npm i

### To run newman:
npx newman run .\collection\customer_api_collection.json -e .\collection\customer_api_env.json

### To generate report:
npm test

-------------------
## Postman Report
![1](https://user-images.githubusercontent.com/38497405/115919149-42f1e500-a49a-11eb-97df-d3a755ac36ea.PNG)

## Newman Report
![2](https://user-images.githubusercontent.com/38497405/115919194-53a25b00-a49a-11eb-8aa6-9e4030d92807.PNG)
