--SAYISAL TASARIM LAB. UZEM ÖDEV?
--365243 EZG? MERAL

Library IEEE;
Use IEEE.std_logic_1164.all;

Entity tekB is
  Port ( aVec      : in  std_logic_vector( 2 downto 0 );
         bVec : out std_logic_vector ( 3 downto 0 ));
  end entity;
  
Architecture mimari of tekB is
             signal eslik: std_logic;
Begin 
  
  eslik <= aVec(0) xor aVec(1) xor aVec(2);
  bVec <= aVec & not eslik;
end mimari;
    

