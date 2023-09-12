# Upgrade

## Sidebar

Use the method `make` instead of `schema` in order to separate the main sections from the sidebar sections.
 
```php
Sidebar::make()->([
    // Components for the main section here
],[
    // Components for the sidebar section here
])
```