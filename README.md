# Swift-Playground-Project

import Foundation

// Definindo uma constante com o valor inicial "Steve"  

let firstName = "Steve"  

// Definindo uma variável do tipo String opcional com valor inicial "Jobs"  

var lastName: String? = "Jobs"  

// Print usando interpolação entre a constante e a variável opcional  

print("Nome completo: \(firstName) \(lastName ?? "Worniak")")  

// Optional binding na variável lastName  

if let unwrappedLastName = lastName {  

    // Print usando interpolação entre a constante e a variável desembrulhada  
    
    print("Nome completo desembrulhado: \(firstName) \(unwrappedLastName)")  
}  
