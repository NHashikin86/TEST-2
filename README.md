# TEST-2
package test2;

import java.net.InetAddress;
import java.net.NetworkInterface;


public class Test2 {

        public static void main(String[] args) {
        // ipaddress for current / localhost
           // display the ipaddress 
            
        InetAddress ip;
        try{
            ip = InetAddress.getLocalHost();
            System.out.println("Your IP Address : " + ip.getHostAddress());
            
            NetworkInterface network = NetworkInterface.getByInetAddress(ip);
            
        }
        
        
                
        
    }
    
}
