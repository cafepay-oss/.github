# CafePay

CafePay helps cafes take orders, manage menus, and record payments.
Customers use a Persian web app.
Staff use separate screens for tables, kitchen orders, delivery orders, and receipts.

Start with the [local setup guide](https://github.com/cafepay-oss/cafepal/blob/main/LOCAL_SETUP.md).
It runs the backend and web apps through Docker Compose.
You can start with an empty database and create a demo cafe.
Local payments use a simulator and need no bank credentials.

| Repository | What it does |
| --- | --- |
| [cafepal](https://github.com/cafepay-oss/cafepal) | Shared backend, database models, and local setup |
| [cafepay-webapp](https://github.com/cafepay-oss/cafepay-webapp) | Customer menus, orders, and checkout |
| [cafepay-admin](https://github.com/cafepay-oss/cafepay-admin) | Staff tools, order management, and receipt review |
| [cafepay_waiter](https://github.com/cafepay-oss/cafepay_waiter) | Table orders and kitchen updates |
| [cafepay-printer-driver](https://github.com/cafepay-oss/cafepay-printer-driver) | Desktop receipt printing |
| [node-notif](https://github.com/cafepay-oss/node-notif) | Browser push notifications |
| [cafepay-app](https://github.com/cafepay-oss/cafepay-app) | Unfinished Flutter mobile app |

For card transfers, customers upload a receipt after payment through their bank app.
Staff confirm the transfer against the bank account before recording payment.
See the [card transfer guide](https://github.com/cafepay-oss/cafepal/blob/main/CARD_TRANSFERS.md) for the complete process.

## Project status

The web apps and backend have a working local setup and automated tests.
The project still uses older Django, Vue, and build dependencies.
Public hosting needs dependency upgrades and separate deployment testing.
The mobile app remains unfinished.
Live bank payments, SMS delivery, and physical printers need separate checks.

These repositories start with reviewed copies of the current source.
The public history excludes older credentials and restricted font files.
Local databases, receipt uploads, and source archives are not part of this release.

## Help improve CafePay

Read the [contribution guide](https://github.com/cafepay-oss/.github/blob/main/CONTRIBUTING.md) before sending a change.
Use each repository's issues for bugs you can reproduce and changes you want to propose.
Report security problems through [private vulnerability reporting](https://github.com/cafepay-oss/.github/blob/main/SECURITY.md).

CafePay code uses the MIT license.
Fonts and other third-party files keep their own licenses.
Each repository includes the relevant notices.
