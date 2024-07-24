# Introduction

## Site used

- I have chosed a Django App that is freely available on a very popular YT channel, Traversy Media [https://www.youtube.com/@TraversyMedia](https://www.youtube.com/@TraversyMedia), that has a detailed video on its build by Dennis Ivy with an attached repo provided.

- The reason for this is that it creates the scenario of us testing a site we ourselves have not build and also provides explanations of how it was built.

- Video: [https://www.youtube.com/watch?v=PtQiiknWUcI](https://www.youtube.com/watch?v=PtQiiknWUcI)
- Repo: [https://github.com/divanov11/StudyBud/](https://github.com/divanov11/StudyBud/)

I have absorbed the repo into this test framework and made no changes other than adding tests.

## Additional apps

I have set up an `ecommerce` app which just serves as a basis for tests and has no website.

This has FK and M2M tables for `Category`, `Product`, `Order`, `ProductCategory` and use `base.User`, from the StudyBud app, as well.

## Asides

## Layers of test

- DB:SQL
- DB:ORM
- Models
- Views
- Forms
- Middleware
- API
- E2E

## Files are docs

The files are heavily documented so that these are the articles on each topic.

The book has its own articles.

<br>