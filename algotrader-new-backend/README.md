# AlgoTrader Backend - Vercel Ready

## 🚀 Quick Deploy to Vercel

### Method 1: Drag & Drop
1. **Zip this entire folder**
2. **Go to [vercel.com](https://vercel.com)**
3. **Drag the zip file** to deploy
4. **Done!** Your API will be live

### Method 2: GitHub
1. **Create new GitHub repository**
2. **Upload all files** from this folder
3. **Connect to Vercel**
4. **Auto-deploy** on every push

## 🔧 Environment Variables

Set these in Vercel dashboard:
```
UPSTOX_API_KEY=3620db9f-0c99-4df1-8278-51a44f19f14f
UPSTOX_API_SECRET=14v44ngg4s
```

## 📋 API Endpoints

- **Health Check**: `/api/health`
- **Market Data**: `/api/market/quotes`
- **Portfolio**: `/api/portfolio`
- **Place Order**: `/api/trading/place-order`
- **Execute Strategy**: `/api/strategy/execute`

## ✅ Features

- ✅ **Vercel Serverless** - Optimized for Vercel deployment
- ✅ **CORS Enabled** - Works with any frontend
- ✅ **Error Handling** - Graceful error responses
- ✅ **Mock Data** - Realistic trading data for testing
- ✅ **Environment Variables** - Secure API key management
- ✅ **Multiple Endpoints** - Complete trading API

## 🧪 Test After Deployment

Visit: `https://your-backend.vercel.app/api/health`

Expected response:
```json
{
  "status": "healthy",
  "version": "2.0.0",
  "upstox_configured": true,
  "environment": "production",
  "timestamp": "2025-06-18T..."
}
```

## 🔄 Real-time Data

The API generates realistic mock data that changes on each request:
- Market prices fluctuate realistically
- Portfolio values update dynamically
- Order execution simulated accurately

Perfect for testing and demonstration!

