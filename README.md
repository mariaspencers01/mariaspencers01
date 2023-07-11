```php
<?php

namespace MariaSpencer;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Google',
                'position' => 'SDE'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            C++::class,
            Python::class,
            JAX::class,
            PyTorch::class,
            Docker::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
