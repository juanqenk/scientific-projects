# Cookiecutter Scientific Projects

_A clean, minimal, standardized, but flexible project structure for research._


#### [Project homepage](https://github.com/juanqenk/scientific-projects)


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project:
------------

    cookiecutter https://github.com/juanqenk/scientific-projects

or 

     cookiecutter gh:juanqenk/scientific-projects


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── LICENSE
├── README.md          <-  README template
├── CONTRIBUTING.md  <-  CONTRIBUTING template
├── AUTHORS.md 
├── data
│   ├── raw      <- Unprocessed data 
│   ├── cooked      <- Processed data.
│
├── docs
├── results
├── code 
│   ├── bin 
│   ├── scr
├──
```




## Built With

* [Cookiecutter](https://github.com/cookiecutter/cookiecutter)

## Authors

* **Juan Cuenca**  - [web personal](https://juanqenk.github.io/juan/)


## License

This project is licensed under the BSD License - see the [LICENSE.md](LICENSE.md) file for details


