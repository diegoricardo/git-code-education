# Primeiro Push

Para realizar o primeiro push foram realizados os seguintes passos, tendo-se em vista que o repositório no GitHub já havia sido criado:

```sh
$ git commit -m "Primeiro commit"
$ git remote add origin https://github.com/diegoricardo/git-code-education.git
$ git push origin master
```
A saída foi a seguinte:

```sh
Counting objects: 28, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (15/15), done.
Writing objects: 100% (28/28), 2.16 KiB | 0 bytes/s, done.
Total 28 (delta 6), reused 0 (delta 0)
To https://github.com/diegoricardo/git-code-education.git
 * [new branch]      master -> master
```

Dessa forma, nosso branch master foi criado em nosso repositório central no GitHub e podemos compartilhar nosso código com os outros.