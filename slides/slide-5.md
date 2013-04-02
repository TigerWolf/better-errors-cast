## Other Notes

###Vagrant 

If using Vagrant you will need to do something extra

Better errors has some inbuilt security

You will need to add ``BetterErrors::Middleware.allow_ip! ENV['TRUSTED_IP'] if ENV['TRUSTED_IP']`` to your development environment

And you will need to run your server with: ``TRUSTED_IP=66.68.96.220 rails s``

# Any Questions?
