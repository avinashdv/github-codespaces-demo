# github-codespaces-demo
this is for a demo

## Standard Output

* Filtering Examples: Sort & Uniq

echo -e "Apple\nCarrot\nBanana" | sort
echo -e "Apple\nCarrot\nBanana\nApple" | sort | uniq -

* Grep
echo -e "Apple\nCarrot\nBanana\nApple" | sort | uniq -c | grep Apple

ps -ef | grep python

echo 1993

echo 1993 | rev

## Standard Input

* Ask for user input

read -p 'File: ' FILENAME

* put it into a script

less > fruits.txt


## Standard Error

* Create Error
ls -l /var/FAKEDIR

* Write error to a file
ls -l /var/FAKEDIR 2>error.txt

* Throw Error away
ls -l /var/FAKEDIR 2>/dev/null




