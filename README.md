Storenvy Oauth Client
=====================

A starter application for building on the Storenvy OAuth API.

#Getting Started

1. Clone the project folder onto your computer.

2. Register a new application at [http://developers.storenvy.com/oauth/applications](http://developers.storenvy.com/oauth/applications).

        # Callback URL (change the domain, if you're using something else)
        http://storenvy-oauth-client.com/users/auth/storenvy/callback

3. Run in the console: `bundle install; rake db:reset`

4. Set [pow](http://pow.cx/) to point `storenvy-oauth-client.dev` to the app's project folder.

5. Create .powenv environment variables locally or on heroku

		# sample .powenv file
		export STORENVY_APP_ID="234235436gfd"
		export STORENVY_SECRET="32235trgfdbvc"		

		# setup keys on heroku
		heroku config:add STORENVY_APP_ID="234235436gfd" STORENVY_SECRET="32235trgfdbvc"

6. Build something awesome!