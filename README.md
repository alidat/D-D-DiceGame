# D-D-DiceGame
// An dice rolling application for Dungeons and Dragons

public class DnDDice{

    private int d4, d6, d8, d10, d12, d20, secondd10;
 
    public DnDDice(){
        roll();
    
    }
    public void roll(){
        d4 = ((int)Math.random()*4) + 1;
        d6 = ((int)Math.random()*6) + 1;
        d8 = ((int)Math.random()*8) + 1;
        d10 = ((int)Math.random()*10) + 1;
        d12 = ((int)Math.random()*12) + 1;
        d20 = ((int)Math.random()*20) + 1;
        secondd10 = ((int)Math.random()*10) + 1;
        
    }
    public int getd4(){
        return d4;
    }
    public int getd6(){
        return d6;
    }
    public int getd8(){
        return d8;
    }
    public int getd10(){
        return d10;
    }
    public int getd12(){
        return d12;
    }
    public int getd20(){
        return d20;
    }
    public int secondd10(){
        return secondd10;
    }
    public String toString(){
        
        String d4result = Integer.toString(d4);
        
        return d4result;
        
    }
}

