# PHP Snippets Pro 🚀

> Modern PHP snippet manager with a beautiful UI and seamless VS Code integration, optimized for PHP 8.x development.

## Features ✨

- **Beautiful Snippet Browser**: Modern, searchable UI to browse and manage your snippets
- **50+ Ready-to-Use Snippets**: Carefully crafted for modern PHP 8.x development
- **Type-Safe Templates**: Full support for PHP's type system and attributes
- **Modern PHP Features**: Support for enums, attributes, named arguments, and more
- **Customizable**: Add, edit, or remove snippets to match your coding style
- **Quick Access**: Use Command Palette or dedicated Snippet Browser
- **Smart Search**: Find snippets by name, description, or content
- **Category Organization**: Snippets organized by purpose (Classes, Types, Error Handling, etc.)

## Quick Start 🏃‍♂️

1. Open Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Type "Show PHP Snippets"
3. Choose between:
   - **Quick Pick**: Fast snippet insertion
   - **Browser**: Full snippet management

## Available Snippets 📝

Here are some commonly used snippets to get you started:

```php
// Class Definition (prefix: cls)
class ClassName
{
    private $property;

    public function __construct($params)
    {
        // Constructor body
    }
}

// Constructor Property Promotion (prefix: ctor)
public function __construct(
    private string $property,
) {
    // Constructor body
}

// Try-Catch Block (prefix: tc)
try {
    // Your code here
} catch (\Exception $e) {
    error_log($e->getMessage());
}

// Enum Definition (prefix: enum)
enum Status
{
    case PENDING = 'pending';
    case ACTIVE = 'active';
    case INACTIVE = 'inactive';
}

// Match Expression (prefix: match)
$result = match ($value) {
    1 => 'one',
    2 => 'two',
    default => 'other',
};

// Array Methods (prefix: map, filter, reduce)
$result = array_map(function($item) {
    return $item * 2;
}, $array);
```

## Snippet Categories 📚

- **Classes**: Class definitions, traits, interfaces
- **Types**: Enums, type declarations, union types
- **Error Handling**: Try-catch blocks, error logging
- **Arrays**: Map, filter, reduce operations
- **Functions**: Method definitions, callbacks
- **Async**: Promise-like operations, async functions
- **Control Flow**: Match expressions, conditionals
- **Properties**: Getters, setters, property promotion

## Managing Snippets 🛠️

### Adding New Snippets:
1. Open Snippet Browser
2. Click "Add New Snippet"
3. Fill in prefix, description, and code
4. Save!

### Editing Snippets:
1. Find snippet in browser
2. Click "Edit"
3. Modify and save

## Key Bindings ⌨️

- Open Quick Pick: `Ctrl+Shift+P` → "Show PHP Snippets"
- Open Snippet Browser: `Ctrl+Shift+P` → "Show PHP Snippets (Browser)"

## Why PHP Snippets Pro? 💡

- **Modern PHP Focus**: Optimized for PHP 8.x development practices
- **Beautiful Interface**: Modern, searchable UI that enhances productivity
- **Type-Safe Templates**: Promotes type-safe PHP development
- **Comprehensive Coverage**: From basic patterns to advanced PHP 8.x features
- **Active Development**: Regular updates with new PHP features
- **Performance**: Light-weight and fast, won't slow down your editor

## Contributing 🤝

Found a bug or have a feature request? [Open an issue](https://github.com/Shellomo/vscode_ext_php-snippets-pro/issues)!

Want to contribute? [Fork the repository](https://github.com/Shellomo/vscode_ext_php-snippets-pro) and submit a pull request.

## Release Notes 📋

### 1.0.0
- Initial release
- 50+ PHP snippets optimized for PHP 8.x
- Full support for modern PHP features
- Snippet Browser UI with category organization
- Search functionality
- Custom snippet management

## Support 💪

Like this extension? [Rate it on the marketplace](https://marketplace.visualstudio.com/items?itemName=Shellomo.php-snippets-pro)!

---

**Enjoy modern PHP development with PHP Snippets Pro! ⚡**