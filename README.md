case 2:
		cout<<"enter daily spending limit : ";
		cin>>dailySpendingLimit;
		cout<<"enter weekly spending limit : ";
		cin>>weeklySpendingLimit;
		break;

  oid deposit() 
{
	double amount;
	cout<<"enter amout to be deposited : ";
	cin>>amount;
    if (amount > 0) {
            initialBalance1 = initialBalance1 + amount;
        cout << "Deposit successful. Current balance: " << initialBalance1 << endl;
    } else {
        cout << "Invalid deposit amount. Please enter a positive value." << endl;
    }
}  


int transfer(int &amount)
 {
    int bank;
	char name;	
	cout<<"  ----------------------------------------------------------------------------------------"<<endl;
 	cout<<"  1. HBL"<<endl;
	cout<<"  ----------------------------------------------------------------------------------------"<<endl;
 	cout<<"  2. UBL"<<endl;
	cout<<"  ----------------------------------------------------------------------------------------"<<endl;
 	cout<<"  3. Ishaaq Bank"<<endl;
	cout<<"  ----------------------------------------------------------------------------------------"<<endl;
 	cout<<"  4. Rana Bank"<<endl;
	cout<<"  ----------------------------------------------------------------------------------------"<<endl;
 	cout<<"  5. MetroBoomin Bank"<<endl;
	cout<<"  ----------------------------------------------------------------------------------------"<<endl;
 	cout<<"  Choose the bank : "<<endl;
 	cin>>bank;
 	switch(bank)
 	{
 		int ibn, pintransfer;
 		char surechoice;
 		case 1: 
 		cout<<"Enter IBAN of the reciever:"<<endl;
 		cin>>ibn;
 		cout<<"Do you want to proceed with the transaction ? (y/n) : ";
 		cin>>surechoice;
 		if(surechoice == 'y')
 		{
 			cout<<"transfer successful";
 			
			                 
 			
		 }
		 else if (surechoice == 'n')
		 {
		 	cout<<"transaction cancelled";
		 }
		 else
		 {
		 	cout<<"invalid input";
		 }
		
 		break;
 		case 2: 
 		cout<<"Enter IBAN of the reciever:"<<endl;
 		cin>>ibn;
 		cout<<"Do you want to proceed with the transaction ? (y/n) : ";
 		cin>>surechoice;
 		if(surechoice == 'y')
 		{
 			cout<<"transfer successful";
 			
		 }
		 else if (surechoice == 'n')
		 {
		 	cout<<"transaction cancelled";
		 }
		 else
		 {
		 	cout<<"invalid input";
		 }
		
 		break;
 		case 3: 
 		cout<<"Enter IBAN of the reciever:"<<endl;
 		cin>>ibn;
 		cout<<"Do you want to proceed with the transaction ? (y/n) : ";
 		cin>>surechoice;
 		if(surechoice == 'y')
 		{
 			cout<<"transfer successful";
 			
		 }
		 else if (surechoice == 'n')
		 {
		 	cout<<"transaction cancelled";
		 }
		 else
		 {
		 	cout<<"invalid input";
		 }
		
 		case 4: 
 		cout<<"Enter IBAN of the reciever:"<<endl;
 		cin>>ibn;
 		cout<<"Do you want to proceed with the transaction ? (y/n) : ";
 		cin>>surechoice;
 		if(surechoice == 'y')
 		{
 			cout<<"transfer successful";
 			
		 }
		 else if (surechoice == 'n')
		 {
		 	cout<<"transaction cancelled";
		 }
		 else
		 {
		 	cout<<"invalid input";
		 }
		
 		break;
 		case 5: 
 		cout<<"Enter IBAN of the reciever:"<<endl;
 		cin>>ibn;
 		cout<<"Do you want to proceed with the transaction ? (y/n) : ";
 		cin>>surechoice;
 		if(surechoice == 'y')
 		{
 			cout<<"transfer successful";
 			
		 }
		 else if (surechoice == 'n')
		 {
		 	cout<<"transaction cancelled";
		 }
		 else
		 {
		 	cout<<"invalid input";
		 }
		
 		break;
	}
	
 }
