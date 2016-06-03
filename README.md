

## APPOINTMENT API

### HTTParty Get

HTTParty.get 'http://api/v1/appointments.json'

### HTTParty Post

HTTParty.post('http://api/v1/appointments', body: { user: {name: "Json", age: "22", city: "Plainsville", state: "NV"} })

### HTTParty Patch

HTTParty.patch('http://api/v1/appointments/4', body: { user: {name: "Jason"} })

### HTTParty Delete

HTTParty.delete 'http://api/v1/users/4' 

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.
