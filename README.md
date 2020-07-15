```php
<?php

namespace IT4Life;

class MeAtWork extends Profile
{
    public function company(): string
    {
        return 'Sun*';
    }
    
    public function position(): string
    {
        return 'Developer';
    }

    public function skills(): array
    {
        return [
            'PHP',
            'JavaScript',
            'Laravel',
            'Linux',
        ];
    }

    public function goals(): array
    {
        return [
            'To be DevOps engineer',
            'To contribute to open source',
            'To build a product',
        ];
    }
}
```
