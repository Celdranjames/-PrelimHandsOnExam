import java.util.Scanner ;
import java.util.HashMap ;
public class PrelimhandsOnExam_2ndSEm {
    static HashMap<String,HashMap<Double,Integer>> inventory = new HashMap<>();
    static Scanner scanner = new Scanner(System.in);
    
    static void addItem(){
        System.out.println("Enter item name: ");
        String itemName = scanner.nextLine();
        System.out.Println("Enter item Price: ");
        double itemPrice = Double.parseDouble(scanner.nextLine());
        System.out.println("Enter item quantity; ");
        int itemQuantity = Integer.parseInt(scanner.nextLine());
        HashMap<Double,Integer> hashHolder = new HashMap<>();
        hashHolder.put(itemPrice,itemQuantity);
        inventory.put(itemName,hashHolder);
        System.out.println();
        
    static void setQuantity(){
        double priceHolder = 0;
        int quantityHolder = 0;
        System.outprintln("Enter item name: ");
        String itemName = scanner.nextLine();
        System.out.println("Enter new quantity: ");
        int setQuantity = Integer.parseInt(scanner.nexyLine());
        if(inventory.containsKey(itemName)){
            priceHolder = j;
            quantityHolder = setQuantity;
            hashHolder.put(priceHolder,quantityHolder);
            inventory.put(item,hashHolder);
            
 }
        
    Static void displayInventory(){
        System.out.println("Inventory");
        
    }
        
        
        
        
         }
    }
}
