# verilog_notebook
Codes for verilog, for reference.

module top_module( 
    input a, 
    input b, 
    output out );
    
assign out = a & b ;          // AND
assign out = ~ (a | b);       // NOR
assign out = ~ ( a ^ b);      // XNOR 


endmodule
