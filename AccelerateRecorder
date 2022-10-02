echo "$(date).acrec" > last.tmp
name="cat last.tmp"
echo $name
mkdir acrec
cd acrec
while true
do
echo -e  "[$(date|cut -c 12-19)]\n$(termux-sensor -s "KXTJ3 Accelerometer" -n 1 |sed -n 4,6p)" >> "$name"
clear
cat $name
done
echo "Saved in ~/accrec/$name"
