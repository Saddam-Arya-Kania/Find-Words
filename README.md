/* # Find-Words
Tugas Pemrograman Terstruktur. */
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

	
    
    return 0;
}
