>> % FREY Modeli Parametrləri

a= 0.2;

b= 0.1;

c= 5;

deyerleri aralığı

x = 0:0.1:10;FREY Modeli funksiyası

y = a.*exp(-b.*x).*sin(c.*x);

% Qrafik çizimi

plot(x,y);xlabel('X');

ylabel('Y');

title( FREY Modeli Qrafiki');

grid on;


