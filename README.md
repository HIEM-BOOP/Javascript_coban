// Bài 1
/* Tính tổng hai số  */

// input: 2 số a và b ;
// ouput : Tổng hai số a và b;

function sum(a, b) {
  var sum = a + b;

  // TODO: Tạo biến a và b và truyền cho hai tham số các giá trị ;

  return sum;
}
console.log("Tổng là " + sum(12, 4));
/* Hiệu */
function brand(a, b) {
  var brand = a - b;

  // TODO : Tạo biến a và b  truyền cho hai biến một giá trị;

  return brand;
}

console.log("Hiệu là " + brand(30, 4));

/* tích */

function area(a, b) {
  var area = a * b;
  // TODO : truyền đầu vào là a và b sau đó xuất ra và gắn giá trị cho cả hai biến ;

  return area;
}

console.log("Hiệu là " + area(10, 10));

/* Thương */

function division(a, b) {
  var division = a / b;

  // TODO : truyền đầu vào là a và b sau đó xuất ra và gắn giá trị cho cả hai biến ;

  return division;
}

console.log("Thương là " +division(30,3));

/* 2.Tính bình phương của một số */

// input : a;
// ouput : sqrt số a ; 

function sqrt(a){
    var sqrt = Math.pow(a, 2);
    
    // TODO : cho biến là a và xuất ra nó và truyền a một giá trị ;

    return sqrt ;

}
    console.log(`Bình phương  ` + sqrt(10));

    /* Tìm số lớn nhất giữa hai số */

    function numbers(a, b) {
        
        var numbers = [a,b];

        var maxNumber = Math.max.apply(Math, numbers);
        
        return maxNumber;
    }
    console.log(`Số lớn nhất là :`+(numbers(11,22)));

    /* Tìm số nhỏ nhất giữa hai số  */

    function NhoNhat(a, b){
        var numbers = [a,b];
        
        var minNumber = Math.min.apply(Math, numbers);

        return minNumber;
    }

    
    console.log(`Số nhỏ nhất là : `+(NhoNhat(10,11)));
/* Tinh gia tri AVG */
    function avg(a, b){
        var avg = (a + b) / 2;
        // TODO 

        return avg;
    }

    console.log("avg: " + avg(15,5));

    /* Tinh so du cua 2 so */

    function tinhLayPhanDu(a,b) {
        var c = a % b;
        
        
        // TODO

        return c;

    }

    console.log(`Kết quả chia lấy phần dư a%b: ` + tinhLayPhanDu(15,4));
    
    console.log('kết quả chia lấy phần dư b%a: '+ tinhLayPhanDu(4,15));

    /* Chia hết cho một số hay ko  */

    function check(a,b){
         
        var checks = a % b;
        if(checks === 0)
        {
            console.log(a + " Chia hết cho "+b)
        }
        else {
            console.log(a + " Không Chia hết cho "+b);
        }
        var dao = b % a ;
        if (dao === 0) {
            console.log(b + " chia hết cho "+a);
        }
        else {
            console.log(b + " không chia hết cho "+a);
        }

        return checks;
        
    }

    console.log(check(12,4));
    



/* Tính chu vi hình chữ nhật  */

    function tinhHCN(a,b){
        var P = (a + b) * 2 ;
        console.log("Chu vi diện tích hình chữ nhật là : " + P);
        var S = a * b;
        console.log("Chu vi diện tích hình chữ nhật là : " + S);
        
        return P,S ;
    }

    // tinhHCN(3,3)
    
    tinhHCN(5,4);
    
    /* Tính chu vi hình tròn */
    function tinhHTron(a, b){
       
        var A = (Math.pow(a, 2) * Math.PI);
        console.log("Chu vi diện tích hình tròn : " + A);

        var C = (2*b*(Math.PI));
        console.log(" Chu vi chu vi hình tròn " + C);

    }

    tinhHTron(2,6);

    /* 2. Chuỗi */
   
        var S1 , S2 , S3 , S4 , S5 ;

        S1 = 'Hiêm xấu trai ';
        S2 = 'và ko có gì';
        
        var S = S1 + S2      

    console.log(S);
