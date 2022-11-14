# Banking-System
#include <iostream>

using namespace std;

class BankingApplication {
};

class BankAccount {
private:
    string accountID;
    double balance;
public:
    BankAccount() {
        balance = 0;
    }

    BankAccount(double x);

    BankAccount getAccountID();

    BankAccount getBalance();

    BankAccount setAccountID();

    BankAccount setBalance();

    BankAccount withdraw(double amount);

    BankAccount deposit(double amount);

};

BankAccount::BankAccount(double x) {
    balance = x;
}

BankAccount getAccountID() {

}

BankAccount getBalance() {

}

BankAccount setAccountID() {

}

BankAccount setBalance() {

}

BankAccount withdraw(double amount) {

}

BankAccount deposit(double amount) {

}

class SavingsBankAccount {
private:
    double minimumBalance = 1000;
public:
    SavingsBankAccount(double minBalance, double initialBalance);

    SavingsBankAccount withdraw(double amount);

    SavingsBankAccount deposit(double amount);
}; 
