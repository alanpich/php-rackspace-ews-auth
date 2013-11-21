# alanpich/rackspace-ews-auth

Lightweight authentication against a Rackspace hosted Microsoft Exchange account.

## Installation
````sh
$ composer install --save alanpich/rackspace-ews-auth
````


## Getting Started
````php
$rackspace = new AlanPich\Auth\RackspaceEws\AuthProvider;
$user      = 'alan@example.com';
$password  = 'password123';

if($rackspace->authenticate($user,$password)){
    // woohoo!
} else {
    // failure
};
````