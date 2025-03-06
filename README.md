# PolyAI Spellinfo

A Laravel-based project for spell information management.

## Requirements

- PHP 8.1 or higher
- Composer
- Node.js & NPM
- MySQL/PostgreSQL

## Installation

1. Clone the repository
2. Run `composer install`
3. Run `npm install`
4. Copy `.env.example` to `.env` and configure your environment
5. Run `php artisan key:generate`
6. Run database migrations: `php artisan migrate`
7. Compile assets: `npm run dev`

## Development

- Run `npm run dev` for development
- Run `npm run build` for production

## Testing

```bash
php artisan test
```

## License

This project is open-sourced software licensed under the MIT license.