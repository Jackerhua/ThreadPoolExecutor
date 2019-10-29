public class Thread1 implements Runnable {
   Object lock;
   public void run() {  
       synchronized(lock){
         ..do something
       }
   }
}
