# Expense-Tracker-Server ![GitHub repo size](https://img.shields.io/github/repo-size/dhyanpatel110/Expense-Tracker-Server)

## Endpoints

- CATEGORIES API

  |      HTTP Method      | Endpoint |       Usage        |       Body        |
  | :-------------------: | :------: | :----------------: | :---------------: |
  | /api/categories   |   POST    |   create categories   | "type", "color" |
  | /api/categories |   GET    |  get all categories    |

- TRANSACTION API

  |      HTTP Method      | Endpoint |       Usage        |       Body        |
  | :-------------------: | :------: | :----------------: | :---------------: |
  | /api/transaction   |   POST    |  create transaction   | "name", "type", "amount" |
  | /api/transaction |   GET    |  get all transaction   |
  | /api/transaction |   DELETE    |  delete transaction by id   | "id" |

- LABELS API

  |      HTTP Method      | Endpoint |       Usage        |       Body        |
  | :-------------------: | :------: | :----------------: | :---------------: |
  | /api/labels   |   GET    |   get all labels   |
