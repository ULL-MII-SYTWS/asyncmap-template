# Template para la Práctica Asyncmap

* [Descripción de la práctica](https://ull-mii-sytws.github.io/practicas/asyncmap.html)

## Usage

Once you have written the missing code:

```
➜  asyncmap-solution git:(main) npm i

up to date, audited 3 packages in 696ms

found 0 vulnerabilities
➜  asyncmap-solution git:(main) npm test

> asyncmap-solution@1.0.0 test
> npm run clean; npm run create-inputs 3 7; npm run my-async.mjs; cmp --silent test/output.txt test/expected.txt && echo 'OK'


> asyncmap-solution@1.0.0 clean
> rm -f test/f*.txt test/output.txt


> asyncmap-solution@1.0.0 create-inputs
> scripts/create-inputs.bash ${npm_package_config_numfiles} ${npm_package_config_size} "3" "7"


> asyncmap-solution@1.0.0 my-async.mjs
> node my-async.mjs -f test/f*.txt -o test/output.txt

OK
```