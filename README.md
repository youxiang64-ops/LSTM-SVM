数据集说明
领域场景：钢铁制造 - 热轧厂
数据量：400条
核心字段：
event_id: 唯一的事件ID，用于关联所有信息。
equipment_name: 设备名称，具体到设备和位置。
equipment_code: 设备资产编码，用于唯一标识。
timestamp: 故障报告时间。
fault_description: 由现场操作工或巡检员填写的故障现象描述，语言风格口语化、场景化，并隐含了多模态信息。
technician_diagnosis: 由专业维修技术员给出的精准、书面化的故障诊断结论。
maintenance_actions: 记录了为解决该故障所采取的具体维修步骤。
root_cause_analysis: 对故障根本原因的分析，是更高层次的知识。
related_multimodal_data: 一个JSON格式的字符串，描述了与本次事件关联的时序数据文件名、图像文件名、以及参考的设备手册章节。这使得你可以模拟一个完整的多模态检索过程。
