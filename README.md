

## Installation
Installation for the package can be done via pip.

```commandline
    pip install newsapi-python
```

## Usage

After installation, import client into your project:

```python
from newsapi import NewsApiClient
```

Initialize the client with your API key:

```python
api = NewsApiClient(api_key='XXXXXXXXXXXXXXXXXXXXXXX')
```

### Endpoints
 
#### Top Headlines

```python
api.get_top_headlines(sources='bbc-news')
```
#### Everything

```python
api.get_everything(q='bitcoin')
```
#### Sources

```python
api.get_sources()
```
