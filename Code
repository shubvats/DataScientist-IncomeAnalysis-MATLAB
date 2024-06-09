APR=[5.99 9.669 8.89 4.113 6.983 5.67 10.032];
disp('Annual Percentage Rate for the months of September, October, November, December, January, February, March ');
disp(APR);
disp('Average APR');
d=mean(APR);
disp('Income of the person before interest to be paid for the respective months');
income=[6430 6200 6700 7100 6560 6130 6400 ];
disp(income);
disp('Average income of the person ');
avginc=mean(income);
disp(avginc);
disp('Cumulative income for the person');
totinc=sum(income);
disp(totinc);
nexttile
stairs(income)
xlabel('value of income');
title('STEP PLOT OF INCOME VALUES BEFORE INTEREST IS DEDUCTED');
disp(' Calulation of monthly interest rate "r" for the give values of APR');
%Calling function to calculate value of monthly interest 'r'
b=calci(APR);
disp(b);
nexttile
disp(' Stair graph of different values of r');
stairs(b)
xlabel('value of r');
title('STEP PLOT OF VALUES OF R');
disp('Average monthly interest r');
c=mean(b);
disp(c);
disp('Values of the income of the person after deducting interest to be paid');
%Calling function to calculate value of income after interest deduction
newincome=comp(b,income);
disp(newincome);
disp('Average income of the person after interest deducted');
avgsal=mean(newincome);
disp(avgsal);
disp('Net Cumulative Salary of the person after deducting interest');
netsalary=sum(newincome);
disp(netsalary);
disp('Step graph of the new income of the person');
nexttile
stairs(newincome)
xlabel('value of income');
title('STEP PLOT OF VALUES OF NEW INCOME AFTER INTEREST');
