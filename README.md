<p align="center">Laravel Militane - Octanes steriodal brother on ms</p>

<p align="center">
<a href="https://github.com/laravel/octane/actions"><img src="https://github.com/laravel/octane/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/octane"><img src="https://img.shields.io/packagist/dt/laravel/octane" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/octane"><img src="https://img.shields.io/packagist/v/laravel/octane" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/octane"><img src="https://img.shields.io/packagist/l/laravel/octane" alt="License"></a>
</p>

## Introduction

Laravel Octane supercharges your application's performance by serving your application using high-powered application servers, including [FrankenPHP](https://frankenphp.dev), [Open Swoole](https://openswoole.com), [Swoole](https://github.com/swoole/swoole-src), and [RoadRunner](https://roadrunner.dev). Octane boots your application once, keeps it in memory, and then feeds it requests at supersonic speeds.

## ⚡ Enhanced for Swoole & OpenSwoole

**This version is specifically optimized for [Swoole](https://github.com/swoole/swoole-src) and [OpenSwoole](https://openswoole.com)** and includes enhanced ticker functionality with **millisecond precision timing**. 

### Key Enhancements:
- **Millisecond Precision Tickers**: Execute callbacks with sub-second accuracy (down to milliseconds)
- **Fluent Ticker API**: Use `.milliseconds(500)` or `.seconds(2)` for intuitive interval configuration
- **Enhanced Performance**: Optimized timing mechanisms for high-frequency operations
- **Better Testing**: Comprehensive test coverage for millisecond-precision functionality

### Recommended Usage:
For the best experience and to leverage all enhanced features, we recommend using this version with:
- **Swoole 5.0+** or **OpenSwoole 22.0+**
- PHP 8.1+ for optimal performance

## Official Documentation

Documentation for Octane can be found on the [Laravel website](https://laravel.com/docs/octane).

## Contributing

Thank you for considering contributing to Octane! You can read the contribution guide [here](.github/CONTRIBUTING.md).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

Please review [our security policy](https://github.com/laravel/octane/security/policy) on how to report security vulnerabilities.

## License

Laravel Octane is open-sourced software licensed under the [MIT license](LICENSE.md).
