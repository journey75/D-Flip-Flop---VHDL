--This is example.vhd, used for Lab0.
--Read over this code and determine the purpose.
--Further, what hardware does this represent?
LIBRARY ieee;
USE ieee.std_logic_1164.all;
entity example is
port( d: IN std_logic_vector(3 downto 0);
clk: IN std_logic;
q: OUT std_logic_vector(3 downto 0));
end example;
--Begin the architecture, why is it called mixed?
architecture mixed of example is
signal internal_d: std_logic_vector(3 downto 0);
begin
--You should expect a comment explaining the process in your own code.
--However, this is omitted here so you can figure it out!
process(clk)
begin
if(rising_edge(clk)) then
internal_d <= d;
else
internal_d <= internal_d;
end if;
end process;
q <= internal_d;
end mixed;