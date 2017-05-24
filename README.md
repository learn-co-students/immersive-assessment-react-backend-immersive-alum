# React Assessment Backend

This is the Rails backend you should use to supply your [React front-end
application](https://github.com/learn-co-curriculum/immersive-assessment-react-frontend) with data.

## Setup

1. Clone down the repo.
2. Make sure you have postgres running (you should see the elephant in the menu bar at the top of your screen)
3. Run `rake db:setup `
4. Remember that your frontend React app is running on port `3000`. You should therefore specify to run your Rails server on a different port. To do this, start up the server with `rails s -p 3001`. Your server will be running on `http://localhost:3001`
5. The endpoint you need to hit is the transactions index route: `http://localhost:3001/transactions`

