# mock_api

- 백엔드에서 API가 완성될때까지 무작정 기다리는 게 아니라, mock data를 만들어 데이터가 들어오는 상황을 미리 대비하고 데이터에 맞게 UI가 의도한대로 구현되는지 먼저 확인
- mock data를 만드는 과정에서 백엔드 API에서 보내주는 response가 어떤 형태인지, key-value값을 확인하고 미리 mock data와 백엔드 response의 형태를 맞춰보면서 개발 진행

## Installation

```bash
# Default.
$ yarn init -y
$ yarn add json-server

# Start!
$ yarn json-server --watch db.json --port 5001

# package.json
  "scripts": {
    "server-start": "json-server --watch db.json --port 5001"
  }
```

## Specs

- mock_api
- Postman
