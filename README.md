# 学生成绩查询系统

## 部署 URL
http://grade-system-yourname.s3-website-us-east-1.amazonaws.com

## 功能
- 学生登录查询成绩（时段控制）
- 教师上传/管理成绩
- AWS DynamoDB 存储
- React 前端 + Node.js 后端

## 测试账号
- **学生**：2025002 / 李四
- **教师**：T001 / 李老师

## AWS 组件（8 种）
| 组件 | 功能 |
|------|------|
| DynamoDB | 数据存储 |
| S3 | 静态托管 |
| IAM | 权限控制 |
| ... | ... |

## 运行步骤
1. `cd backend && node server.js`
2. `cd frontend && npm start`
