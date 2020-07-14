# gunther

#include<iostream>
int main(){
    int age;
     std::cout<<"enter your age:"<<age;
     std::cin>>age;
     if(age>=18){
        std::cout<<"YAY!! You are elliginle to vote. Go on.. ";
     }
     else{
         std::cout<<"Sorry:: you are not elligible";
     }
    return 0;
}
