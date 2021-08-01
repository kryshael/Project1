
#My First Shell Script

roulette_dealer_finder_by_time.sh


#!/bin/bash
cat 0310_Dealer_schedule 0312_Dealer_schedule 0315_Dealer_schedule

echo "The above schedules are for 03/10, 03/12, and 03/15. Please enter the information below to verify who is working."

echo "Enter a 4 digit date (mmdd): "
read Var1

echo "Enter a 2 digit time (hour): "
read Var2

echo "Enter am or pm: "
read Var3




if [ "$Var1 $Var2 $Var3" = "0310 12 am" ]

then

grep 12 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 01 am" ]

then

grep 01 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 02 am" ]

then

grep 02 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 03 am" ]

then

grep 03 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 04 am" ]

then

grep 04 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 05 am" ]

then

grep 05 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 06 am" ]

then

grep 06 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 07 am" ]

then

grep 07 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 08 am" ]

then

grep 08 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 09 am" ]

then

grep 09 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 10 am" ]

then

grep 10 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 11 am" ]

then

grep 11 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 12 pm" ]

then

grep 12 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 01 pm" ]

then

grep 01 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 02 pm" ]

then

grep 02 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 03 pm" ]

then

grep 03 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 04 pm" ]

then

grep 04 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 05 pm" ]

then

grep 05 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 06 pm" ]

then

grep 06 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 07 pm" ]

then

grep 07 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 08 pm" ]

then

grep 08 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 09 pm" ]

then

grep 09 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 10 pm" ]

then

grep 10 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0310 11 pm" ]

then

grep 11 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0310_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 12 am" ]

then

grep 12 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 01 am" ]

then

grep 01 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 02 am" ]

then

grep 02 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 03 am" ]

then

grep 03 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 04 am" ]

then

grep 04 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 05 am" ]

then

grep 05 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 06 am" ]

then

grep 06 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 07 am" ]

then

grep 07 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 08 am" ]

then

grep 08 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 09 am" ]

then

grep 09 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 10 am" ]

then

grep 10 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 11 am" ]

then

grep 11 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 12 pm" ]

then

grep 12 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 01 pm" ]

then

grep 01 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 02 pm" ]

then

grep 02 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'



elif [ "$Var1 $Var2 $Var3" = "0312 03 pm" ]

then

grep 03 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 04 pm" ]

then

grep 04 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 05 pm" ]

then

grep 05 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 06 pm" ]

then

grep 06 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 07 pm" ]

then

grep 07 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 08 pm" ]

then

grep 08 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 09 pm" ]

then

grep 09 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 10 pm" ]

then

grep 10 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0312 11 pm" ]

then

grep 11 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0312_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 12 am" ]

then

grep 12 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 01 am" ]

then

grep 01 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 02 am" ]

then

grep 02 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 03 am" ]

then

grep 03 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 04 am" ]

then

grep 04 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 05 am" ]

then

grep 05 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 06 am" ]

then

grep 06 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 07 am" ]

then

grep 07 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 08 am" ]

then

grep 08 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 09 am" ]

then

grep 09 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 10 am" ]

then

grep 10 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 11 am" ]

then

grep 11 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep AM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 12 pm" ]

then

grep 12 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 01 pm" ]

then

grep 01 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 02 pm" ]

then

grep 02 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 03 pm" ]

then

grep 03 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 04 pm" ]

then

grep 04 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 05 pm" ]

then

grep 05 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 06 pm" ]

then

grep 06 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 07 pm" ]

then

grep 07 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 08 pm" ]

then

grep 08 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 09 pm" ]

then

grep 09 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 10 pm" ]

then

grep 10 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'




elif [ "$Var1 $Var2 $Var3" = "0315 11 pm" ]

then

grep 11 /03-student/Homework/Lucky_Duck_Investigations/Roulette_Loss_Investigation/Dealer_Analysis/0315_Dealer_schedule | grep PM | awk '{print $1,$2,$5,$6}'



else echo "Uh-Uh-Uh, you didn't say the Magic Word."


fi