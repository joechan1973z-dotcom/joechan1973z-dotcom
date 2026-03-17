<div style="width: 100%; height: 300px; display: flex; justify-content: center; align-items: center; gap: 20px; padding: 20px;">
    <!-- 杭州 & 加州 双城生活 -->
    <div style="width: 100px; height: 100px; background-color: #ff793f; animation: pulse 2s infinite;"></div>
    <div style="width: 100px; height: 100px; background-color: #05d9e8; animation: pulse 2s infinite;"></div>

    <!-- 设计师 & 创业者 -->
    <div style="width: 100px; height: 100px; background-color: #ff2a6d; animation: bounce 2s infinite;"></div>
    <div style="width: 100px; height: 100px; background-color: #05ffa1; animation: bounce 2s infinite;"></div>
</div>

<style>
@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.1); }
    100% { transform: scale(1); }
}

@keyframes bounce {
    0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
    40% { transform: translateY(-30px); }
    60% { transform: translateY(-15px); }
}
</style>
