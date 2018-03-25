# c-
Some code that I think need to be reserved.
//使用类实现copy
#include "stdafx.h"
#include <iostream>
 using namespace std;
  class CPt {public: CPt() {}; ~CPt() {}; float m_x, m_y;
 bool copy(CPt a2) { *this = a2; if (this->m_x&&this->m_y)  return false; } void show() {  cout << m_x << m_y; }
};
int main(){ CPt a1, a2; cin >> a2.m_x >> a2.m_y; a1.copy(a2); a1.show(); system("pause"); return 0;}
