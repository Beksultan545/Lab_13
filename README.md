# Lab 13 — Mobile Navigation

**Student Name:** Kopzhasar beksultan
**Date:** 10.04.2026

---

## Task 1 — Stack Navigation

Экрандар арасында стек арқылы навигация жасайды.

### Экрандар
- **HomeScreen** — басты экран
- **ProfileScreen** — профиль (userId параметрі)
- **SettingsScreen** — баптаулар

### Route Parameters
```typescript
navigation.navigate('Profile', { userId: '123' });
const userId = route.params?.userId ?? 'default';
```

### Іске қосу
```bash
cd task1 && npx expo start
```

---

## Task 2 — Bottom Tab Navigation

4 таб + әр табта өз Stack Navigator.

### Табтар
| Tab | Сипаттама |
|-----|-----------|
| Home | Басты экран |
| Search | Іздеу |
| Notifications | Хабарландырулар (badge: 5) |
| Profile | Профиль |


### Іске қосу
```bash
cd task2 && npx expo start