# homework2_12_9
# 수치해석(Matlab)

![12 9-1](https://user-images.githubusercontent.com/58453290/70115469-1cfc5280-16a3-11ea-9351-142cd5912b7d.JPG)

![12 9-2](https://user-images.githubusercontent.com/58453290/70115471-1e2d7f80-16a3-11ea-9cca-09203b0e4ede.JPG)

x=[1.5;1.5]; %x,y값


j=[2*x(1) 2*x(2);2*x(1) -1] %Jocobian Matrix

f=[x(1)^2+x(2)^2-5;x(1)^2-x(2)-1]%f1(x,y);f2(x,y)

inv(j)  %[j]^1

%Xnew = Xold-j\f

x=x-j\f %first order

x=x-j\f %second order

x=x-j\f %third order

x=x-j\f %fourth order

x=x-j\f %fifth order
