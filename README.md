# miami-scheduler
Website for scheduling courses at Miami University - Oxford. www.miamischeduler.com

## Setup
Clone the repo.
cd into the main directory.
run an `npm install`
### Database
```
brew install postgres
brew services start postgres
npm run db:create
npm run db:setup
npm run db:import
```
