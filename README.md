# Payment Rails Ruby Library

[![Latest Stable Version](https://poser.pugx.org/paymentrails/ruby-sdk/v/stable.png)](https://packagist.org/packages/paymentrails/ruby-sdk)

The Payment Rails Ruby library provides integration access to the Payment Rails API.

## Requirements

Ruby version >= 2.4.3 is required.

## Installation & Usage

### Clone the SDK

```bash
git clone https://github.com/PaymentRails/ruby-sdk.git
```

### Build & Install the gem

```bash
cd ruby-sdk
bundler install
gem build paymentrails.gemspec
gem install paymentrais-[version].gem
```

## Getting Started

```Ruby

require 'paymentrails'

client = Gateway.new(Configuration.new('YOUR-API-KEY', 'YOUR-SECRET-KEY', 'production'))

recipient = client.recipient.find('R-1234567abcdefg')
print recipient.id
```

## Documentation for API Endpoints

All URIs are available at http://docs.paymentrails.com/
