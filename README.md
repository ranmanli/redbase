to run the code:
cd build
cmake ..
make
./dbcreate Test
./redbase Test
create table data (int i, location m);
insert into table data (1, [1, 2, 3, 4]);
***the format of location must be [d1, d2, d3, d4]***
select * from data;
hello this is change
