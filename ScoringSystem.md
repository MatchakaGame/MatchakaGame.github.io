# Matchaka Scoring System Documentation

## Core Point Sources

### 1. Base Level Reward
- 30 points per level completed
- Fixed reward regardless of performance

### 2. Level Bonus
Points awarded upon level completion:
- Levels 1-9: 5 points × (level - 1)
  Example: Level 5 gives 20 bonus points (5 × 4)
- Levels 10-25: 40 + 8 points × (level - 9)
  Example: Level 15 gives 88 bonus points (40 + 8 × 6)
- Levels 26-34: 168 + 12 points × (level - 25)
  Example: Level 30 gives 228 bonus points (168 + 12 × 5)
- Levels 35+: 276 + 15 points × (level - 34)
  Example: Level 40 gives 366 bonus points (276 + 15 × 6)

### 3. Speed Bonus
Points per second of remaining time:
- Levels 1-9: 1.0 points/second
- Levels 10-25: 1.5 points/second
- Levels 26-34: 2.0 points/second
- Levels 35+: 2.5 points/second

### 4. Multiplier Chain Bonus
- Base: (multiplier - 1) × 10 points
- Scaling by level:
  - Levels 1-9: Base bonus
  - Levels 10-25: Base bonus × 1.5
  - Levels 26-34: Base bonus × 2.0
  - Levels 35+: Base bonus × 2.5

## Average Total Points Per Level

### Early Game (1-9)
- Base Reward: 30
- Level Bonus: 0-40
- Speed Bonus: ~10-20 (10-20 seconds saved × 1.0)
- Multiplier Bonus: ~10-20
Total Range: 50-110 points

### Mid Game (10-25)
- Base Reward: 30
- Level Bonus: 48-168
- Speed Bonus: ~15-30 (10-20 seconds saved × 1.5)
- Multiplier Bonus: ~15-30 (base × 1.5)
Total Range: 108-258 points

### Grandmaster (26-34)
- Base Reward: 30
- Level Bonus: 180-276
- Speed Bonus: ~20-40 (10-20 seconds saved × 2.0)
- Multiplier Bonus: ~20-40 (base × 2.0)
Total Range: 250-386 points

### Master (35+)
- Base Reward: 30
- Level Bonus: 276+ (increases by 15 per level)
- Speed Bonus: ~25-50 (10-20 seconds saved × 2.5)
- Multiplier Bonus: ~25-50 (base × 2.5)
Total Range: 356+ points

## Notes
1. Base time per level is 30 seconds
2. Time penalties increase with difficulty:
   - Levels 1-9: 5 second penalty
   - Levels 10-34: 10 second penalty
   - Levels 35+: 15 second penalty
3. Points increase significantly with level progression due to:
   - Higher level bonuses
   - Increased speed bonus multipliers
   - Larger multiplier chain bonuses
4. Master levels (35+) offer highest point potential
5. Maintaining multipliers becomes increasingly valuable in higher levels
6. Actual scores may vary based on:
   - Pattern matching speed
   - Accuracy (avoiding mismatches)
   - Time management
   - Multiplier chain maintenance
7. New players receive 1000 initial points
8. Debug mode provides 10000 points and 3 time stop tokens for testing

## Store Item Prices
- Continue Token: 3500 points
- Level Skip Token: 5000 points
- Time Stop Token: 2500 points 