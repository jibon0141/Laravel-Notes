## Project Cloing From Git And Setup In Local

```bash
# 1. Clone the repository
git clone <repository-url>

# 2. Go to project folder
cd project-folder

# 3. Copy environment file
cp .env.example .env

# 4. Install PHP dependencies
composer install

# 5. Generate application key
php artisan key:generate

# 6. Create database manually (via phpMyAdmin)

# 7. Run migrations
php artisan migrate

# 8. Seed database (optional)
php artisan db:seed

# 9. Link storage
php artisan storage:link

# 10. Run the server
php artisan serve
```

## If Project Have alpine,react or vue Dependences (Then Run This Extra Command)

```bash
# Install Node dependencies
npm install

# (Optional) Update packages
npm update

# Run development build
npm run dev

# OR production build
npm run build
```
## Project Deployment To Live Server Through Git

2. If SubDomain
```bash
## Create SubDomain

*cPanel->Domains->create a new domain
* enter domin name like this: subdomain.maindomain.com/in/xyz
* don't select share document root as it will select the main domain and this sub Domain will open the main domain website.
* Select or enter the root path of the created folder earlier.
```

