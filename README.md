# E-commerce Background

## Table of Contents

* [Description](#description)
* [Code Examples](#code-examples)
* [Important links](#important-links)
* [Questions](#questions)

## Description

The purpose of this project was to create the backend for an ecommerce business.


## Code Examples
Example of Code 

```js
router.put('/:id', (req, res) => {
  Category.update(
    {
      category_name: req.body.category_name
    },
    {
      where: {
        id: req.params.id
      }
    }
  )
```
Example of Code 

```js
   id: {
      type: DataTypes.INTEGER,
      allowNull: false,
      primaryKey: true,
      autoIncrement: true
    },
    category_name: {
      type: DataTypes.String,
      allowNull: false
    }    
```

## Important Links
[GitHub Repository](https://github.com/keekerr/E-commerce-Back-End)

## Questions

If you have any questions regarding this project, please feel free to contact me at this email: keeley.s.sprouse@gmail.com

Other examples of projects I have worked on can be viewed on Github via this link: [keekerr](https://github.com/keekerr)
