# S-function
Sine function
//MATLAB 正弦函数
x1=1:1:10
y1=6:1:16
s=fun(x1,y1)
function s=fun(x,y)
 xp=(x,0);
 yp=(0,y);
 zp^2=x^2+y^2;
 s=x/zp;
end 
//C语言  正弦函数
void main()
{
  int x;
  int y;
  scanf("%d%d",&i,&y)
  int z;
  z^2=x^2+y^2;
  s=x/z;
  prinf("s=%f\n",s);
  return 0;
}
