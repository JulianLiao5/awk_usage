# awk_usage

1. awk 'NR%2==0' DRAW.txt > DRAW_DONE.txt
2. awk 'BEGIN {FS=" "} {print $1 " " $2 " " $3 " " $4 " " $5 " " $6 " " $7 " " $8 " " $9}' imu_origin_with_temp.csv > imu.csv
