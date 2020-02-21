# Puzzle 1 - Count rows of a csv file

The [csv-sampple.csv](./csv-sample.csv) has 1024 rows and you can verify this by opening it in Excel. If you open the file using a plain text editor such as notepad, you will notice that it has 1028 lines. 

Write a script with one of the following languages to count rows of a csv file. Your script must read [csv-sampple.csv](./csv-sample.csv) and count csv rows and that is 1024.
* PowerShell
* Bash
* Python

You may also choose to write a console program in C# and .NET Core instead of writing a script.

### What to submit: All your source code in a single text file.



# Puzzle 2 - Build a Docker Image

Create a (linux) docker image with Web API which returns your name and email address.

Example docker image can be found at [seyongo/whoami](https://hub.docker.com/repository/docker/seyongo/whoami)

Try the sample.
```
docker pull seyongo/whoami:latest
docker run -it --rm -p 8080:80 --name sample seyongo/whoami:latest
```

Browse http://localhost:8080/api/email and see what it returns.

```json
{
    "displayName":"Se Yong Oh",
    "emailAddress":"seyong@seyong.net"
}
```

Create your own docker image which returns your name and email address, then publish it to Dockerhub.

### What to submit: Your dockerhub image
