# cpp1
swing 1주차 스터디

#include <iostream> <cstring>
using namespace std;
int main() 
{
	
	cout << "당신의 이름은 무엇입니까? :" ;

	char name[10]; //문자열 개수 지정
	cin.getline(name, 10, '\n'); //cin.getline 공백포함한 문자열 입력
	
	cout << "반갑습니다." << name << "님.\n\n";

	cout << "---------SWING 30-----------"<< endl;
	int coke; // 변수 콜라의 가격 선언
	int water; //변수 삼다수의 가격 선언
	int fanta; //변수 환타의 가격 선언

	int c_number; //콜라의 개수
	int w_number; //삼다수의 개수
	int f_number; //환타의 개수


	cout << "음료의 가격 입력을 시작합니다.\n\n";
	
	
	 cout << "콜라의 가격 :" ;
	 cin >> coke; // 입력 콜라의 가격

	 
	 cout << "삼다수의 가격 :" ;
	 cin >> water;

	cout << "환타의 가격 :" ;
	cin >> fanta ;
	cout << "" << endl;

	cout << "개수를 입력해주세요.\n\n";
	
	cout << "콜라 수량 :";
	cin >> c_number; //입력 콜라 개수
	
	cout << "삼다수 수량 :" ;
	cin >> w_number;

	
	cout << "환타 수량 :" ;
	cin >> f_number, '\n';

	cout << "----------------------------" << endl; //라인 출력

	int price; //최종 가격
	price = coke * c_number + water * w_number + fanta * f_number; //최종 가격 계산식

	cout << "500원 할인받아 총" << price - 500 << "원 입니다." << endl; //500원 할인

	return 0;

	
}
