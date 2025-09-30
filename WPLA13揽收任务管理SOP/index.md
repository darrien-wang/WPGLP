---
layout: default
title: "揽收任务管理SOP (调度子任务)"
permalink: /WPLA13揽收任务管理SOP/
---

[← 返回首页](/WPGLP/) | [🔼 上级: 分拣仓调度SOP](/WPGLP/WPLA13分拣仓调度-任务列表SOP/)

<div style="background: #fff3cd; padding: 10px; margin: 10px 0; border-left: 4px solid #ffc107; border-radius: 3px;">
ℹ️ <strong>说明</strong>: 本文档是"WPLA13分拣仓调度任务列表SOP"的子任务文档，专门说明揽收任务的操作流程。
</div>

---

## 1. 概述

**仓库代码**: WPLA13  
**仓库类型**: 分拣仓  
**适用岗位**: 仓库调度员  
**版本**: V1.0  
**生效日期**: 2025-09-30

## 2. 系统链接和工具

### 2.1 系统登录信息
- DMS系统账号: WPLA13
- 密码: Abcd123456
- DMS揽收任务系统: https://dms.wpglb.com/pickup/task/list
- DMS主线管理系统: https://dms.wpglb.com/mainline/mainlineManage/listt

### 2.2 相关表格
- **提货仓车辆配置表**: https://docs.google.com/spreadsheets/d/1IRZqAdMEs52wEJyEF3qkjWM_xJvBJEOE/edit?rtpof=true

## 3. 揽收任务类型

揽收任务分为两种类型：

### 3.1 类型一：外部揽收（司机去提货仓揽货）
**任务描述**: 调度员安排司机去各个提货仓揽收货物，运回WPLA13分拣仓

### 3.2 类型二：入库揽收（仓库接收司机送来的货物）
**任务描述**: 司机将货物送到WPLA13仓库，仓库人员进行揽收入库操作

---

## 4. 类型一：外部揽收任务流程

### 4.1 操作流程图

<div style="background: #f6f8fa; padding: 20px; margin: 20px 0; border-radius: 6px; border: 1px solid #d0d7de; overflow-x: auto;">
<div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 10px; min-width: max-content;">
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">查看客户群</span>
<span style="font-size: 20px; color: #0969da;">→</span>
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">确定提货仓</span>
<span style="font-size: 20px; color: #0969da;">→</span>
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">安排车辆</span>
<span style="font-size: 20px; color: #0969da;">→</span>
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">通知司机</span>
<span style="font-size: 20px; color: #0969da;">→</span>
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">DMS新增任务</span>
<span style="font-size: 20px; color: #0969da;">→</span>
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">生成BOL</span>
<span style="font-size: 20px; color: #0969da;">→</span>
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">发送司机</span>
<span style="font-size: 20px; color: #0969da;">→</span>
<span style="background: #0969da; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">跟进执行</span>
</div>
</div>

**作业时间**: 每天早上开始  
**责任人**: 调度员

### 4.2 详细操作步骤

#### 步骤1: 查看客户微信群通知
**操作说明**:
- 每天早上第一件事：查看各个客户微信群
- 确认当日需要去哪些提货仓揽收
- 记录每个提货仓的货物数量信息
- 特别关注货量提示，判断是否需要大型车辆

#### 步骤2: 确定提货仓和车辆配置

**第一类提货仓（周一至周五揽收）**:
- DWLAX
- USLAX17  
- USLAX08
- **重点注意**：周一、周二DWLAX货量通常较大，可能需要53尺货车
- 根据客户群中的货物数量决定车辆尺寸

**第二类提货仓（周日至周五揽收）**:
- COCA
- FNT
- ONT1
- WPLA
- WPLA3
- WPLA4
- WPLA11
- WPLA13
- WPLA15
- WPLA16
- WPLA17

**第三类提货仓（每日关注客户微信群更新）**:
- YLLA
- LAWLE1
- LAWLW2
- LAKST
- **注意**：这些提货仓的揽收安排需每日在客户微信群中查看最新通知

#### 步骤3: 车辆安排和派遣
1. 打开**提货仓车辆配置表**，查看每个提货仓对应的车辆尺寸要求
2. 根据当日货量和经验判断需要安排的车辆数量和尺寸
3. 考虑特殊情况（如周一、周二DWLAX的大货量）
4. **通知司机**：每天必须通知司机去哪个提货仓揽货
5. 明确告知司机提货地点、时间、注意事项

**车辆尺寸选择要点**:
- 参考提货仓车辆配置表的标准要求
- 结合客户群中的货量信息
- 考虑历史经验（如周一、周二DWLAX需要大车）
- 宁可车大不要车小，避免装不下需要二次派车
- 53尺货车适用于大货量情况

#### 步骤4: 在DMS系统中新增揽收任务
1. 登录DMS系统: https://dms.wpglb.com/pickup/task/list
2. 使用账号WPLA13/Abcd123456登录
3. 进入揽收任务管理界面
4. 点击"新增揽收任务"
5. 填写揽收信息：
   - 提货仓代码
   - 预计货量
   - 车辆尺寸要求
   - 揽收时间
6. 分配司机

#### 步骤5: 生成和发送司机BOL
1. 在DMS系统中生成司机BOL
2. 确认BOL信息准确无误：
   - 提货仓地址
   - 货物信息
   - 车辆信息
   - 司机信息
3. 将BOL发送给指定司机

#### 步骤6: 任务跟进
1. 跟踪揽收任务执行状态
2. 与司机保持沟通，确认到达和装货情况
3. 如遇货量超预期，及时调整车辆安排
4. 记录揽收完成情况和实际货量
5. 更新车辆配置经验数据

---

## 5. 类型二：入库揽收任务流程

### 5.1 操作流程图

<div style="background: #f6f8fa; padding: 20px; margin: 20px 0; border-radius: 6px; border: 1px solid #d0d7de; overflow-x: auto;">
<div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 10px; min-width: max-content;">
<span style="background: #2da44e; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">司机到达</span>
<span style="font-size: 20px; color: #2da44e;">→</span>
<span style="background: #2da44e; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">获取提货单</span>
<span style="font-size: 20px; color: #2da44e;">→</span>
<span style="background: #2da44e; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">通知仓库人员</span>
<span style="font-size: 20px; color: #2da44e;">→</span>
<span style="background: #2da44e; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">开始揽收入库</span>
<span style="font-size: 20px; color: #2da44e;">→</span>
<span style="background: #2da44e; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">扫描登记</span>
<span style="font-size: 20px; color: #2da44e;">→</span>
<span style="background: #2da44e; color: white; padding: 10px 15px; border-radius: 6px; font-weight: bold;">完成确认</span>
</div>
</div>

**作业时间**: 13:00-14:00（卸车前完成）  
**责任人**: 调度员

### 5.2 详细操作步骤

#### 步骤1: 获取提货单
1. 登录DMS系统: https://dms.wpglb.com/mainline/mainlineManage/listt
2. 使用账号WPLA13/Abcd123456登录
3. 查看并打印当日提货单
4. 确认司机信息和预计到达时间

#### 步骤2: 提货单交接
1. 将电子版提货单发送给仓库相关人员
2. 明确告知提货要求和注意事项
3. 确认仓库人员收到并理解提货任务
4. 告知仓库人员司机预计到达时间

#### 步骤3: 司机到达通知
1. 司机到达后及时通知仓库人员
2. 确认货物数量和状态
3. 安排卸货区域和人员

#### 步骤4: 揽收入库操作
1. 仓库人员准备揽收入库
2. 核对提货单信息
3. 检查货物外观状态
4. 按照提货单逐项清点

#### 步骤5: 系统扫描登记
1. 使用PDA或扫描设备
2. 扫描每件货物的条码
3. 在系统中完成入库登记
4. 确认数量和系统记录一致

#### 步骤6: 完成确认和跟进
1. 与司机确认交接完成
2. 在系统中标记揽收完成
3. 记录揽收完成情况
4. 如有异常及时记录和上报

---

## 6. 关键控制点

### 6.1 外部揽收控制点
- 每天早上必须查看客户微信群
- 车辆尺寸必须根据货量合理安排
- 必须提前通知司机揽收任务
- BOL信息必须准确无误
- 保持与司机的实时沟通

### 6.2 入库揽收控制点
- 提货单必须提前发送给仓库人员
- 货物数量必须与提货单一致
- 必须完成系统扫描登记
- 异常情况必须及时记录
- 确保司机和仓库双方确认完成

### 6.3 沟通协调点
- 与客户微信群保持密切关注
- 与司机保持良好沟通
- 与仓库人员及时协调
- 与提货仓保持联系
- 及时反馈任务执行情况

---

## 7. 重要提醒

### 7.1 时间管理
- 外部揽收：早上开始规划，全天跟进
- 入库揽收：13:00-14:00集中处理，14:00前必须完成

### 7.2 质量要求
- 货量判断要准确，避免车辆不够用
- 提货单信息要完整准确
- 系统录入要及时完成
- 异常情况要及时处理

### 7.3 安全注意事项
- 司机装卸货时注意安全
- 货物摆放要稳固
- 重货和易碎品要特别标注
- 遵守仓库安全操作规范

---

**编制**: Darrien，Michael From WPLA13  
**审核**: Tammy  
**批准**: [姓名]  
**修订记录**: V1

