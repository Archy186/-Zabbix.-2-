# Домашнее задание: Мониторинг на основе Zabbix

## Задание 1: Создание шаблона

**Требование:** Скриншот страницы шаблона с названием «Задание 1».

В рамках задания был создан шаблон `Custom CPU RAM Monitor`, содержащий элементы данных для мониторинга загрузки CPU и RAM.

*   **Имя шаблона:** `Custom CPU RAM Monitor`
*   **Элементы данных (Items):**
    *   `CPU Utilization` (Ключ: `system.cpu.util[all,idle]`)
    *   `RAM Utilization` (Ключ: `vm.memory.size[pavailable]`)
