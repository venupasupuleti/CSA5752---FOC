echo "enter name"
read name
echo "enter marks in maths"
read maths
echo "enter marks in science"
read science
echo "enter marks in english"
read english
total=`expr $maths + $science + $english`
if [ $total -ge 240 ];
then
        grade="A+"
elif [ $total -ge 200 ] && [ $total -lt 240 ];
then
        grade="A"
elif [ $total -ge 180 ] && [ $total -lt 200 ];
then
        grade="B"
elif [ $total -ge 160 ] && [ $total -lt 180 ];
then
        grade="C"
else
        grade= "fail"

fi

echo "name: $name"
echo "marks in maths: $maths"
echo "marks in science: $science"
echo "marks in english: $english"
echo "total: $total"
echo "grade: $grade"
