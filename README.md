# CodeIgniter Shared
The purpose is to keep CodeIgniter's system files is a shared place for all my projects, private and public. I don't expect to have anybody use this. We keep CodeIgniter updated and we change how the Controller loads.

### Controller Class Name
For controller names, you will prefix the class name with `Controller_`. So for a controller name App, the class name would be `Controller_App`.

### Setup
To add this as a GIT Submodule, enter this command:

~~~~~
git submodule add git@github.com:srtfisher/codeigniter-shared system-ci
git submodule update --init
~~~~~

CodeIgniter's system file will be in the `system-ci` folder.

### Author
This is made by srtfisher - <http://seanfisher.co/>.
