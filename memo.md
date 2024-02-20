# ROC曲線を描画
fpr, tpr, thresholds = roc_curve(y_true, y_score)
plt.plot(fpr, tpr, label="ROC curve")
plt.xlabel("False Positive Rate")
plt.ylabel("True Positive Rate")
plt.legend()
plt.show()

'age', 年'、
'height(cm)', '身長(cm)',
'weight(kg)', '体重(kg)',
'waist(cm)', 「ウエスト(cm)」、
'eyesight(left)','視力(左)'、
'eyesight(right)', '視力(右)'、
'hearing(left)', '聴覚(左)'、
'hearing(right)', '聴覚(右)'、
'systolic',「収縮期」、
'relaxation', 「リラクゼーション」、
'fasting blood sugar', '空腹時血糖'、
'Cholesterol', 'コレステロール'、
'triglyceride','中性脂肪'、
'HDL', 「HDL」、
'LDL', 「LDL」、
'hemoglobin', 'ヘモグロビン'、
'Urine protein', 「尿タンパク」、
'serum creatinine', 'セラム・クレアチン'、
'AST',AST」、
'ALT', 「オルト」、
'Gtp', 「GTP」、
'dental caries', '虫歯'、

'smoking' '喫煙