# FRAME
CARA INSTAL
jalankan apk.exe
lalu ketik 
create-project

CARA PAKAI FRAME
query("code sql query here")

CARA INSERT
query(INSERT INTO table_name (attribute1,attribute2) VALUES (attribute1,attribute2)");

CARA DELETE
query(DELETE FROM table_name WHERE attribute=attributte");
OR YOU ALSO CAN DO THIS
delete("table_name","primary key=value");

CARA DISPLAY DATA DARI DATABASE
$display=display("SELECT * FROM table_name");

KEMUDIAN PISAHAKAN SEMUA DATA MENGGUNAKAN FOREACH
foreach($display as $data) :

echo $data['attribute1']
//gunakan inline echo agar lebih mudah

endforeach;


