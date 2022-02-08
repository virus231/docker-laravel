### **Creating a Laravel App via the Composer Utility Container**
    1. docker-compose run composer create-project laravel/laravel .

### **Launching Only Some Docker Compose Services**
    1. docker-compose up -d server php  mysql
    2. docker-compose up -d server -- depends_on php mysql
    3. docker-compose up -d --build server

### **Adding More Utility Containers**
    1. docker-compose run --rm artisan migrate