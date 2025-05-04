void main() {
  // هنا كنعلنو على المتغير height اللي غادي نخزنو فيه الطول ديال الشخص فالمتر
  double height = 1.78;

  // هنا كنعلنو على المتغير weight اللي غادي نخزنو فيه الوزن ديال الشخص فالكيلوغرام
  double weight = 125;

  // هنا كنحسبو مؤشر كتلة الجسم BMI باستعمال المعادلة: الوزن ÷ (الطول × الطول)
  double bmi = weight / (height * height);

  // هنا كنطبعو النتيجة ديال BMI فالكونسول
  print("مؤشر كتلة الجسم (BMI) هو: $bmi");
}


void main() {
  // هنا عرفنا متغير سميتو fullName فيه الاسم الشخصي والعائلي ديالك
  String fullName = "Mohammed Ali";

  // هنا كنطبعو عدد الحروف اللي كاينين فالنص
  print("الطول: ${fullName.length}");

  // هنا كنحوّلو النص كامل لحروف كبيرة (Upper Case)
  print("حروف كبيرة: ${fullName.toUpperCase()}");

  // هنا كنحوّلو النص كامل لحروف صغيرة (Lower Case)
  print("حروف صغيرة: ${fullName.toLowerCase()}");

  // هنا كنشوفو واش النص فيه الكلمة "Ali" أو لا، وكنطبعو النتيجة (true أو false)
  print("هل يحتوي على 'Ali'؟ ${fullName.contains('Ali')}");
}
