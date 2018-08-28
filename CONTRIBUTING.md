# Contributing to softlayer-python

We are happy to accept contributions to softlayer-python.  Please follow the
guidelines below.  

* Sign our contributor agreement (CLA) You can find the [CLA here](./docs/dev/cla-individual.md).

* If you're contributing on behalf of your employer we'll need a signed copy of our corporate contributor agreement (CCLA) as well.  You can find the [CCLA here](./docs/dev/cla-corporate.md).
    
* Fork the repo, make your changes, and open a pull request.

* Additional infomration can be found in our [contribution guide](http://softlayer-python.readthedocs.org/en/latest/dev/index.html)


## Code style

Code is tested and style checked with tox, you can run the tox tests individually by doing `tox -e <TEST>`

* `autopep8 -r  -v -i --max-line-length 119  SoftLayer/`
* `autopep8 -r  -v -i --max-line-length 119  tests/`
* `tox -e analysis`
* `tox -e py36`
* `git commit --message="#<ISSUENUMBER> <whatever you did>`
* `git push origin <issueBranch>`
* create pull request




