/*# Find-Words
Tugas Pemrograman Terstruktur.*/
#include <iostream>
#include <cstring>
#include <cstdlib>   

using namespace std;
const int cols = 16, rows = 15;

 char words[rows][cols] = 	   {"tgbwwinterwsesn",
                                "aaunttmmhfoodnb",
                                "jlwcqldzmpmvdmr",
                                "asagmquwvvbsohi",
                                "bwplotanadtpgnc",
                                "rewngodjcpnatnk",
                                "eeotwosbqharrsa",
                                "azcgeswewnaknpb",
                                "dinnerqodlwdcar",
                                "onopkwmparktzcc",
                                "qbfrogmamwpweey",
                                "lqzqnnmrzjjsclg",
                                "mosgzczetdbooto",
                                "pdcrzmsngrdnrpz",
                                "ohnkzwaterjgtra"};

char *getWordVertical(int);
char *reverse(char *);
char *col(char *);
bool findVertical(char *);
bool findHorizontal(char *);

int main()
{
    char word[16];
    int n;
    cin>>n;
    for (int i=0; i<n; i++){
        cin.getline(word,16,'\n');
        if (findVertical (char *)){
		
            cout << "Ada\n";
        }
        else {
		
            cout << "Tidak Ada\n";
        }
    }
    for (int i=0; i<n; i++){
        cin.getline(word,16,'\n');
        if (findHorizontal (char *))
            cout << "Ada\n";
        else 
            cout << "Tidak Ada\n";
    }
or(int m=0; m<xy; m++) {
        nilai[m]=0;
        int pk = vertikal[m], x=0;
        bool ada[pk], result;

        for(int r = 0 ; r < 15 ; r++){
            for(int a=0; a<=(15-pk);
            a++) {
                for(int b=a; b<=a+(pk-1);
                b++) {
                    if(((Y+r)+b) == kata[m][x]) ada[x] = 1;
                    else ada[x] = 0;
                    x++;
                }
                for(int k=0; k<pk;
                k++) {
                    if(ada[k]==1) {
                        result = 1;
                        nilai[m]+=result;
                    }
                else {
                    result = 0;
                    break;
                    }
                    if(nilai[m]==pk) {
                        fix[m]=1;
                        goto next;
                    }
                }
                nilai[m]=0;
                x=0;
            }
        }
for(int c = 0 ; c < 15 ; c++){
            for(int a=0; a<=(15-pk); a++) {
                for(int b=a; b<=a+(pk-1); b++) {
                    if(((Y+b)+c) == kata[m][x]) ada[x] = 1;
                    else ada[x] = 0;
                    x++;
                }
                for(int k=0; k<pk; k++) {
                    if(ada[k]==1) {
                        result = 1;
                        nilai[m]+=result;
                    }
                else {
                result = 0;
                    break;
                    }
                    if(nilai[m]==pk) {
                        fix[m]=1;
                        goto next;
                    }
                }
                nilai[m]=0;
                x=0;
            }
        }
	
    
    return 0;
}
