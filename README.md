# MongoDB JSON Files

## Export
These files are *exported* from my localhost mongodb with the command 

<pre>mongoexport --db store --collection products --out products.json</pre>
<pre>mongoexport --db store --collection orders --out orders.json</pre>
<pre>mongoexport --db store --collection users --out users.json</pre>

You can do the same, or you can use these files with my data.

## Import
The you can *import* these to mongolab

<pre>mongoimport -h ds053964.mongolab.com:53964 -d store_2 -c \<collection> -u \<user> -p \<password> --file \<input file></pre>

This command you can find under the tools tab under your database.


