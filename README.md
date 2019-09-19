# websocket-sandbox / Clean Architecture 


## TODO

- [ ] Add Paese JWT 
- [ ] Add CI setting 
- [ ] Add Dokcer setting
- [ ] Change database mysql tp postgresql
- [ ] Add error tracker (SENTRY Go)
- [ ] Implement notification response (REST)
- [ ] Implement Cloud Server Setting

## Requirements

### Go

```bash
1.11.0 
```

### Insrall goenv and change Go version.

```bash
brew install goenv
goenv install 1.11.6
goenv global 1.11.6
goenv rehash
```

## Config

copy `config.yaml.example` to `config.yaml` and edit params.

## Commands

### Local Test

```bash
make test
```

### Local Build

```bash
make build
```

### Local Serve

```bash
make serve
```
