Pasos para instalar la applicacion desde cero
Laravel     9.28
Jetstream   2.12
Inertia     0.6.3
Vue         3.2.31
Tailwind    3.1

En el directorio code/
    laravel new xt-manager --jet

En el directorio code/xt-manager/
    composer update
    composer install

Crear una BD limpia y actualizar los valores correctos de Database/user/password en el fichero .env

Luego correr las migraciones
    php artisan migrate


Para usar un Layout de Tailwind, 
ir a esta url:
https://tailwindui.com/components/application-ui/application-shells/stacked

copiar el codigo (para VUE) del <template> </template> y 
combinar el codigo del <script></script>

Luego correr estos comandos para instalar dependencias de Tailwind
    npm install @headlessui/vue@latest
    npm install @heroicons/vue

Correr despues de cada cambio
    npm run build

