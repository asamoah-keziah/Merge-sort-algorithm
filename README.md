#include <iostream>

int main(int argc, char** argv) {

	int arraySize = 7;
	int A[7] = [11,21,4,123,12,34,112];
	
	int low = 0;
	int high = arraySize - 1;
	
	mergeSortArray(A, low, high);
	for(int = 0; i < 7; i++){
		cout<< A[i]<< endln;	}
	return 0;
}

void mergeSortArray(int A[], int low, int high){

	if(low < high){
		int mid;
		mid =( low + high)/2;
		
		mergeA(A, low, mid);
		mergeB(A, mid+1; high);
		
		merge(A, low, high, mid);
	}
}
