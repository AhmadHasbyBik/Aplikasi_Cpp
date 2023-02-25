                                             CODE EXPLANATION
                                                by Abeeek

The program is a hotel room rental system that allows customers to choose a room type and rent it for a specified number of days.
Here's how the program works step by step:

1. The program displays a welcome message and a menu of available rooms with their corresponding prices.
=================================================================================
	     cout<<"SISTEM INFORMASI PENYEWAAN KAMAR HOTEL ADITIYA"<<endl;           
       cout<<endl;                                                            
       cout<<"No   Jenis Kamar          Harga "<<endl;                        
       cout<<"1.   Romoela              Rp:500.000"<<endl;                     
       cout<<"2.   Safira               Rp:1.000.000"<<endl;                   
       cout<<"3.   Artacitra            Rp:1.500.000"<<endl;                   
       cout<<"********************************"<<endl;                         
       cout<<endl;                                                             
=================================================================================

2. The program prompts the user to select a room type by entering the room number (1, 2, or 3).
=================================================================================
       cout<<"Pilh Jenis kamar : ";                                            
       cin>>kamar;                                                             
=================================================================================

3. The program determines the room type selected by the user and sets the corresponding room price and room name using an if else statement.
=================================================================================
        if (kamar==1)                                                          
        {                                                                      
          harga=500000;                                                        
          nkamar="Romoela";                                                    
        }                                                                      
        else if (kamar==2)                                                     
        {                                                                      
          harga=1000000;                                                       
          nkamar="Safira";                                                     
        }                                                                      
        else if (kamar==3)                                                     
        {                                                                      
          harga=1500000;                                                       
          nkamar="Artacitra";                                                  
        }                                                                      
=================================================================================

4. The program displays the selected room type, the price per day, and prompts the user to enter the number of days they want to rent the room.
=================================================================================
	  cout<<"Kamar yang anda pilih adalah "<<nkamar<<"                            
    dengan harga Rp:"<<harga<<"/Hari"<<endl;                                       
	  cout<<"Berapa lama anda ingin menyewa kamar tersebut : ";                   
	  cin>>lama;                                                                  
=================================================================================

5. The program calculates the total rental price by multiplying the room price per day by the number of days rented.
markdown
=================================================================================
    bayar=lama*harga;                                                            
=================================================================================

6. The program displays the selected room type, the number of days rented, and the total rental price.
=================================================================================
 	  cout<<endl;                                                                                
 	  cout<<"Jenis kamar pilihan anda : "<<nkamar<<endl;                                          
 	  cout<<"Lama penyewaan anda "<<lama<<" hari"<<endl;                                        
   	cout<<"Total harga penyewaan yang harus anda bayar adalah  Rp; "<<bayar<<endl;   
=================================================================================
