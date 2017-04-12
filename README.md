// # Obj-C_Education_tryobjectivec.codeschool.com

// http://tryobjectivec.codeschool.com/

//Level 1

// Функция, которая выводит на экран текст:

NSLog(@"Hello, Lucy!");

NSString *firstName = @"Lucy";

NSLog(firstName);

NSLog(@"Hello there, %@!", firstName);

NSString *lastName = @"Nezh";

NSLog(@"%@ %@", firstName, lastName);

NSNumber *age = @31;

NSLog(@"%@ is %@ years old.", firstName, age);

// Array is a single variable that hold multiple values:

NSArray *apps = @[@"MyApp1", @"MyApp2", @"MyApp3"];

// Чтобы вывести на экран MyApp2:

NSLog(@"%@", apps[1]);

// Чтобы добавить элемент в массив, нужно заново обозначить все элементы массива. Тип массива уже не надо указывать.

apps = @[@"MyApp1", @"MyApp2", @"MyApp3", @"MyApp4"];

//Чтобы отслеживать, какой рейтинг принадлежит какому приложению, сущ-ет NSDictionary

NSArray *ratings = @[@3, @5];

// Dictionary может содержать несколько пар key/value, разделённых запятой

NSDictionary *person = @{@"First Name": @"Eric"};

NSDictionary *appRatings = @{@"MyApp1": @3, @"MyApp2": @5};

// Доступ к значениям Dictionary осуществляется по ключам

NSLog(@"%@", appRatings[@"MyApp2"]);

NSLog(@"Рейтинг приложения MyApp1 равен %@.", appRatings[@"MyApp1"]);

//Level 2

