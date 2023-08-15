# next-captcha

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A comprehensive and innovative CAPTCHA library in PHP that supports multiple CAPTCHA types.

## Features

- Generate image-based, audio-based, and text-based CAPTCHAs.
- Distinct font variations for CAPTCHA challenges.
- Flexible validation and integration options.
- Examples demonstrating CAPTCHA usage in different scenarios.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Image CAPTCHA](#image-captcha)
  - [Audio CAPTCHA](#audio-captcha)
  - [Text CAPTCHA](#text-captcha)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation

Install the CAPTCHA library using Composer:

```bash
composer require code-lords/next-captcha
```

## Usage
### Image CAPTCHA
To generate and display an image-based CAPTCHA:

```php
// Include Composer autoloader
require_once 'vendor/autoload.php';

use Codelords\NextCapture\CaptchaGenerator\ImageCaptchaGenerator;

$captchaGenerator = new ImageCaptchaGenerator();
$captchaChallenge = $captchaGenerator->generate();
$captchaImagePath = $captchaGenerator->saveImage('/path/to/save');

// Display $captchaImagePath in your HTML form
```
### Audio CAPTCHA
To generate an audio-based CAPTCHA:

```php

// Include Composer autoloader
require_once 'vendor/autoload.php';

use Codelords\NextCapture\CaptchaGenerator\AudioCaptchaGenerator;

$captchaGenerator = new AudioCaptchaGenerator();
$captchaChallenge = $captchaGenerator->generate();
// Output $captchaChallenge as an audio element in your HTML
```

### Text CAPTCHA
To generate a text-based CAPTCHA:

```php
// Include Composer autoloader
require_once 'vendor/autoload.php';

use Codelords\NextCapture\CaptchaGenerator\TextCaptchaGenerator;

$captchaGenerator = new TextCaptchaGenerator();
$captchaChallenge = $captchaGenerator->generate();
// Display $captchaChallenge in your HTML form
```

## Examples
For more detailed usage examples, see the examples directory.

## Contributing
Contributions are welcome! Please read CONTRIBUTING.md for details on how to contribute to this project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

