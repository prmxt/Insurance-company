# **Описание класса Contract**
***
Класс для работы с договорами страховой компании.
# Атрибуты
***
+ AmountOfInsurancePremium : Float - сумма страховой выплаты;
+ Beneficiary : List<Client> - список бенефициаров;
+ BranchOffice : BranchOffice - филиал;
+ ClientBuyer : ModelingProject1::Client - клиент покупатель;
+ ContractNumber : String - уникальный номер договора;
+ DateOfContract : DateTime - дата заключения договора;
+ Documentation : List<Documentation> - список прилагаемых документов;
+ EndContractDate : DateTime - дата окончания действия договора;
+ EndPrice : Float - конечная стоимость;
+ ID : Int - идентификатор договора;
+ Rate : ModelingProject1::Rate - тариф;
+ Worker : ModelingProject1::Worker - работник.