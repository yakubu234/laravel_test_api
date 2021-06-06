# ensure you generate your secret encryption key with 
php artisan jwt:secret

# upon generation you will find your key at the .env
JWT_SECRET=secret_jwt_string_key


# Method	# Endpoint
# POST	    # /api/auth/register
# POST	    # /api/auth/login
# GET	    # /api/auth/user-profile
# POST	    # /api/auth/refresh
# POST	    # /api/auth/logout


# the published collection link
https://documenter.getpostman.com/view/12538701/TzY68ZWY