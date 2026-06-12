# Strainpedia API Examples

Build cannabis apps, AI assistants, WooCommerce stores, directories, and strain comparison tools using the Strainpedia API.

## Live Demo Endpoints

### Blue Dream

https://www.strainpedia.com/wp-json/strainpedia/v1/demo/blue-dream

### Gelato

https://www.strainpedia.com/wp-json/strainpedia/v1/demo/gelato

### OG Kush

https://www.strainpedia.com/wp-json/strainpedia/v1/demo/og-kush

### Northern Lights

https://www.strainpedia.com/wp-json/strainpedia/v1/demo/northern-lights

### Girl Scout Cookies

https://www.strainpedia.com/wp-json/strainpedia/v1/demo/girl-scout-cookies

---

## API Documentation

https://www.strainpedia.com/api/

---

## Features

- Search strains
- Single strain lookup
- Compare strains
- Genetics
- THC ranges
- CBD ranges
- Terpenes
- Effects
- Flavors
- Categories
- Featured images
- WordPress integration
- WooCommerce integration

---

## cURL Example

```bash
curl https://www.strainpedia.com/wp-json/strainpedia/v1/demo/gelato
```

### Authenticated Request

```bash
curl \
-H "x-api-key: YOUR_API_KEY" \
https://www.strainpedia.com/wp-json/strainpedia/v1/search?query=gelato
```

---

## JavaScript Example

```javascript
fetch(
  "https://www.strainpedia.com/wp-json/strainpedia/v1/demo/gelato"
)
.then(response => response.json())
.then(data => console.log(data));
```

---

## Python Example

```python
import requests

response = requests.get(
    "https://www.strainpedia.com/wp-json/strainpedia/v1/demo/gelato"
)

print(response.json())
```

---

## WordPress Example

```php
$response = wp_remote_get(
    'https://www.strainpedia.com/wp-json/strainpedia/v1/demo/gelato'
);

$data = json_decode(
    wp_remote_retrieve_body($response),
    true
);

print_r($data);
```

---

## Subscribe

Developer API access:

https://www.strainpedia.com/api/

---

## Attribution

Apps and websites using Strainpedia API data should include:

Data provided by Strainpedia

https://www.strainpedia.com/
