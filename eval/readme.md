# 评分脚本说明

## task 1
python eval/mc_accuracy.py \
--prediction_path ./data/model/MC_prediction.jsonl \
--answer_path ./data/input/MC_test.jsonl

"eval/mc_accuracy.py" 为评分脚本的绝对或相对路径 \
"--prediction_path" 后为模型预测结果的绝对或相对路径 \
"--answer_path" 后为标准答案的绝对或相对路径
