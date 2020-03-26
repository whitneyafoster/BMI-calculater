# BMI-calculater

function bmiCalculator (weight, height) {
    var BMI = (weight/ (height * height));
    BMI = Math.floor(BMI);
    var interpretation = " ";


if (BMI < 18.5) {interpretation = "Your BMI is " + BMI + " so you are underweight.";
} if (BMI >= 18.5 && BMI <= 24.9) {interpretation = "Your BMI is " + BMI +  " so you have a normal weight."; 
    
} if (BMI > 24.9) {interpretation = "Your BMI is " + BMI + " so you are overweight."; 
} return interpretation
}

console.log(bmiCalculator(60,2))
