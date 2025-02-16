# project
It is my first project.
#include <stdio.h>
int quiz(int original_answer,int user_answer){
    if(original_answer==user_answer){
        printf("Yeah, you got it!!\n");
        return 1;
    }else{
        printf("Ohh No,you lost\n");
        return 0;
    }
}

int main() {
    int n;
    int total_marks=0;
    printf("Hello,Wlecome to our wildddd quizzz!!!!!");
    printf("(Question1)Which continent is the majority of the Amazon Rainforest located on?\na)Africa\nb) Asia\nc) North America    \nd) South America\n");
    printf("Mark the Correct Answer:");
    scanf("%d",&n);
    total_marks+=quiz(4,n);
    printf("Result:-%d",total_marks);
    return 0;
}
