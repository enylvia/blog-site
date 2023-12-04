+++
author = "Aditya Permadi"
title = "MY EXPERIENCE USING GORM"
date = "2023-12-04"
description = "In this post I try to give my experience when using GORM"
tags = [
    "post",
    "gorm",
    "orm"
]
thumbnail= "images/blog-images/gorm-logo.png"
+++

# Start using Object related model (ORM) especially GORM
<hr>

## Introduction

<p style="text-align: justify"> In the process of developing a website, data storage is an important process, especially for a backend. However, in the process of storing data, we also recognize a structural language that is used to run storing the data to the database. This structural language is then made easier to use into ORM. GORM is one of the existing ORMs, GORM is an Object Relational Mapping (ORM) library for Golang. ORM converts data between incompatible type systems using object-oriented programming languages. </p>

## Installing GORM

Installing GORM itself is quite easy. Follow these steps:

1. Visit the official GORM page: [gorm.io](https://gorm.io)
2. To install GORM in your project, use the following command in your terminal:

```bash
  go get -u gorm.io/gorm
```

## Installing SQLite Database Driver

<p style="text-align: justify">After installing GORM, you need to install the database driver that you plan to use in your project. In this example, we'll install the SQLite driver. Run the following command: </p>

```bash
  go get -u gorm.io/driver/sqlite
```
It's quite easy right? to install gorm on the project we are working on. 

## My Experience 
<p style="text-align: justify">While using orm, especially gorm, it helps me to develop applications quickly, because I don't need to write complicated query syntax.
Gorm also offers interesting features with easy usage gorm is one of my choices when I want to develop an application quickly.
But everything must have its own advantages and disadvantages. </p>

### Advantages
* Less boilerplate code and fewer manual SQL queries.
* Straightforward database migrations and schema updates.
* A simple CRUD interface for querying and manipulating database records.
* Many more.. 

### Disadvantages
* Limited control over the underlying SQL queries and database optimization.
* Perfomance.. Yeppp orm will never surpass raw query in terms of performance.
* There may be a significant time investment needed to become proficient in using it.

### Sumary 
<hr>
<p style="text-align: justify">
Maybe that's all the story about my experience when using orm to develop an application or project. The conclusion is that whether you should use ORM or not depends on your needs. If you want to develop applications quickly ORM can be the answer, but if you are concerned with performance and ease of optimization then raw query.

So just learn both, because it will be useful in the future.
</p>