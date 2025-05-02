# Multi-Language Bible JSON Files

This repository contains full Bible texts in multiple languages, structured in a clean JSON format. These rare resources are shared for free to support developers, researchers, linguists, and faith-based projects around the world.

## 📜 Included Languages (so far)

- Twi (Akuapem)
- Ewe
- French
- More coming soon...

## 📁 Format

Each file is a JSON object where:
- The top-level keys are book names (e.g., "Genesis")
- Each book contains chapter numbers as keys
- Each chapter contains verse numbers and their corresponding text

### 📘 Example Structure

```json
{
  "name":"Genesis",
  "testament":"old",
  "chapters":[
    "chapter":"1" || 1,
    "verses":[
      {
        "verse":"1"||1,
        "text":"....................."
      }
    ]
  ]
}
```

## 📦 Use Cases

- Bible reading apps
- Language processing tools
- Scripture-based machine learning models
- Cross-language Bible comparison tools
- Offline Bible apps or websites

## 📄 License

These files are released under the **Creative Commons Zero v1.0 Universal (CC0 1.0)** license.  
You may use, copy, modify, and distribute them freely — without any restrictions.

## 🙏 Acknowledgements

These Bibles are rare and offered freely for the benefit of communities and developers who need local-language scriptures in a usable digital format. If you build something with these, we'd love to hear about it!

## 🔗 Share

You may upload or fork this project, or embed the JSON files in your own apps.
