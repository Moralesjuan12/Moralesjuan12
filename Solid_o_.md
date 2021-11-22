- 👋 Hi, I’m @Moralesjuan12
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Moralesjuan12/Moralesjuan12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package solid;

/**
 *
 * @author LENOVO X1 CARBON
 */
public class Solid {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
    }
    
}

_________________________________________________________________________

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package solid;

/**
 *
 * @author LENOVO X1 CARBON
 */
public class car {
    void accelerate(boolean isCarRace){
        //Acelerate car
        if(isCarRace){
            injectEstraGas();
        }
    }
    void stop(){
        //Stop car
    }
    private void injectEstraGas(){
    //do..
    }

    void accelerate() {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }
}

_________________________________________________________________________

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package solid;

/**
 *
 * @author LENOVO X1 CARBON
 */
public class RaceCar extends car{
    @Override
    void accelerate (){
        injectEstraGas();
        super.accelerate();
        
    }
    private void injectEstraGas(){
    //do...
    }
}


