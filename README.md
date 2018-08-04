# Symfony-Commands
Commands used in symfony development

### Create a new project (Symfony 3)
```
composer create-project symfony/framework-standard-edition Project_Name
```

### Create entity
```
php bin/console doctrine:generate:entity
```

### After creating entities, validate the mappings with the following command:
```
php bin/console doctrine:schema:validate
```

### Creating the Database Tables/Schema
```
php bin/console doctrine:schema:update --force
```
