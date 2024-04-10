int findSingle(int n, int arr[]){
        // code here
        int Xor=0 ;
        for(int i =0 ; i<n ; i++){
            Xor=Xor^arr[i] ;
        }
        return Xor ;
    }
