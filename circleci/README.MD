# CircleCI Challenge Solution

This is the CircleCI solution. Try first yourself before you look up this solution. \
The text for the exercises can be found here:

## Exercise 1
Do a yamllint on the config.yml file in your .circleci directory. 
1. Choose a Python base image
2. Code checkout
3. Install [Yamllint](https://github.com/adrienverge/yamllint)
4. Execute Yamllint only on your circleci config file in the .circleci directory
5. Fix config.yml until the build in circleci is successful 
   
## Exercise 2

Tell yourself your fortune 

1. Look for the cimg base image (ubuntu)
2. Perform an apt-get update
3. Perform an apt-get upgrade
4. Install apt-utils
5. Install fortune
6. Execute /usr/games/fortune
7. Look at Output in circleci
