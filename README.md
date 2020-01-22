# Basic-Typescript

พื้นฐาน Typescript

## ชนิดข้อมูลพื้นฐานใน TypeScript
  - boolean
  
        let isDone: boolean = false;
        
  - Number
  
        let decimal: number = 6.01;
        let hex: number = 0xf00d;
        let binary: number = 0b1010;
        let octal: number = 0o744;
        
  - String 
  
        let color: string = "blue";
        
  - array []
  
        let list: number[] = [1, 2, 3];
        let list: Array<number> = [1, 2, 3]; //generic array type
        
  - Tuple
  
    ช่วยให้เราสามารถแสดงอาร์เรย์ที่มีองค์ประกอบจำนวนคงที่ซึ่งทราบชนิด

        let tuple : [string, number] = ['hello', 555];
        console.log(tuple[0]); //hello
        console.log(tuple[1]); //555

  - Enum 
