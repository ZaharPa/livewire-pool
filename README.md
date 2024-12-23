<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Livewire-pool

Livewire-pool is a Laravel-based web application for creating and managing polls. Users can create polls with multiple options and vote on them in real-time.

### Features

- Create polls with multiple options.
- Vote on polls and see real-time updates.
- User-friendly interface with Livewire components.
- Secure and scalable backend using Laravel.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/ZaharPa/livewire-pool.git
    ```
2. Navigate to the project directory:
    ```sh
    cd livewire-pool
    ```
3. Install dependencies:
    ```sh
    composer install
    npm install
    ```
4. Copy the example environment file and configure it:
    ```sh
    cp .env.example .env
    ```
5. Generate an application key:
    ```sh
    php artisan key:generate
    ```
6. Run the migrations:
    ```sh
    php artisan migrate
    ```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
