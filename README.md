# HALF_SUBTRACTOR
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/df70da69-5a12-4a0d-ab84-a98dad3f7e70)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97)
# module half_subtractor(a,b,diff,borr);
```
input a,b;
output diff,borr;
wire x;
xor (diff,a,b);
not (x,a);
and (borr,x,b);
endmodule
```

# output
![image](https://github.com/Sairam1034/HALF_SUBTRACTOR/assets/161026996/c864d41c-2db8-45f3-9779-58eeb2d71df7)
