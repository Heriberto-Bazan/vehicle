# vehicle

1.- Clonar el proyecto  https://github.com/Heriberto-Bazan/vehicle.git
2.-  ejecuta cp .env.dist .env
3.- Ingresar hasta la carpeta vehículo y ejecutar el comando make run.  
4.- ejecuta el comando make ssh-be para ingresar al proyecto
4.- En el archivo .env DATABASE_URL="mysql://user:password@symfony-api-db:3306/symfony_db"
5.- Dentro del proyecto ejecuta composer install
6.- Ejecuta php bin/console doctrine:database:create
7.- Ejecuta php bin/console doctrine:migrations:migrate
8.- Ejecuta clear cache

