# codetest
class Number:
    def __init__(self, number_1, number_2):
        self.__number_1 = number_1
        self.__number_2 = number_2
    def public (self, num_1, num_2):
        self.__num_1 = self.__number_1
        self.__num_2 = self.__number_2
    def Add(self):
        Sum = self.__number_1 + self.__number_2
        return Sum
    def Minus(self):
        minus = self.__number_1 - self.__number_2
        return minus
    def Multiplication(self):
        multiplication = self.__number_2 * self.__number_1
        return multiplication
    def Divide(self):
        divide = self.__number_1 / self.__number_2
        return divide

def main():
    Pheptinh = Number(2, 4)
    num_1 = float(input())
    num_2 = float(input())
    Pheptinh.public(num_1,num_2)
    Tong = Pheptinh.Add()
    Hieu = Pheptinh.Minus()
    Tich = Pheptinh.Multiplication()
    Chia = Pheptinh.Divide()
    print("%f %f %f %f" %(Tong, Hieu, Tich, Chia))

if __name__ == "__main__":
    main()
