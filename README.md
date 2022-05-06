# Derby
[![CI](https://github.com/weraisedup/book-turbine/actions/workflows/ci_build.yml/badge.svg?branch=main)](https://github.com/weraisedup/book-turbine/actions/workflows/ci_build.yml)

https://bookturbine.com

Generates book recommendations.
=======
# README

### OSX 
```bash
brew cask install docker
```
### OR?
Your favorite myriad other ways.
**Then:**
- `cd` into the book-turbine directory.
- perform `docker compose build`.
- perform `docker compose up`.
- The application should launch, which includes doing any necessary database 
  preparation & seeding and then running the backend + frontend in foreman.
- run `docker exec -it book-turbine-web-1 bundle exec rspec spec` in another 
  terminal tab to run the tests. This requires that `docker compose up` is running.
