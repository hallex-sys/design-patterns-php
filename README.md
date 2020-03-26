# Design Patterns

<img src="https://user-images.githubusercontent.com/55293671/77607982-b7a2ca80-6efa-11ea-9c59-d82fba2e34d6.png" width="250" alt="octocat-hallex">

## Description
Repository of Design Patterns for PHP (Recommended PHP 7.4)

## Tested PHP Version
#### PHP => 7.4

## Design Patterns Added
- [x] Observer ✅
- [ ] Factory  ❌

## How to Use
##### Link: Click [here](http://hallex.zapto.org/desgin-patterns-php/) to go documentation (coming soon)
#### Observer
```php
<?php

$observer = new class extends Observer {
};
$subject = new class extends Subject {
};

OR

class MyObserver extends Observer {}
class MySubject extends Subject {}

Examples of use:

$mySubject = new MySubject;
$myObserver = new MySubject;

$mySubject->attach($observer);
$mySubject->attach($myObserver);
$mySubject->detach($myObserver);
$mySubject->notify();

OR

$subject
	->attach($observer)
	->attach($myObserver)
	->detach($observer)
	->notify();

Debug:

```

## Contributor
```json
{
	"name": "Hállex da Silva Costa",
	"age": 17,
	"role": "Developer",
	"startDate": "18/03/2020",
	"currentDate": "26/03/2020"
}
```

## Attention
##### [Website Hallex](http://hallex.zapto.org/) it's Offline ❌
