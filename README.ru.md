<div align="center">

<img src="docs/icon.png" width="128" alt="Иконка HDRI kit">

# HDRI kit

**Сшивает 360° HDRI из серии фотографий — прямо на вашем Mac.**

[![Платформа](https://img.shields.io/badge/платформа-macOS%2027-blue)](#требования)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-arm64-lightgrey)](#требования)
[![Статус](https://img.shields.io/badge/статус-бета-orange)](#бета-версия)
[![Лицензия](https://img.shields.io/badge/лицензия-бесплатно-green)](LICENSE)

[**Скачать последний DMG →**](https://github.com/x-m4v/HDRI-kit/releases/download/v0.5.0-beta/HDRI.kit.dmg) · [English](README.md)

</div>

## Бета-версия

HDRI kit собирает перекрывающиеся фотографии в панораму 360° × 180° для освещения и фона в 3D. Публичная бета может ошибаться на сложных стыках.

## Новое в 0.5.0 beta

Новая иконка, настраиваемая панель вкладок и два режима сшивки. [Полное описание релиза](https://github.com/x-m4v/HDRI-kit/releases/tag/v0.5.0-beta).

## Требования

Mac на Apple Silicon с macOS 27. Рекомендуется от 16 ГБ памяти.

## Установка

Откройте скачанный DMG и перетащите HDRI kit в «Программы». Если macOS заблокирует первый запуск беты, откройте «Системные настройки → Конфиденциальность и безопасность» и нажмите «Всё равно открыть».

## Быстрый старт

1. На вкладке «Создать» добавьте минимум два перекрывающихся снимка.
2. Выберите «Быстро» для проверки покрытия или оставьте «Максимум» для итоговой сшивки. Нажмите «Сшить панораму».
3. Проверьте стыки в редакторе и экспортируйте EXR, HDR или PNG.

[Все возможности](FEATURES.ru.md) · [Руководство пользователя (HTML)](https://github.com/x-m4v/HDRI-kit/releases/download/v0.5.0-beta/HDRI-kit-RU.html) · [Поддержать проект на Boosty](https://boosty.to/m4v/donate)

## Обратная связь

Нашли баг или есть съёмка, которая не сшивается? [Создайте issue](../../issues) и укажите:
- версию macOS и модель Mac;
- камеру или телефон, объектив и количество фото;
- режим качества;
- скриншот результата, если он неверный.

Пожалуйста, не прикладывайте фото, которые не хотели бы выкладывать публично.

## Благодарности

- [OpenCV](https://opencv.org) (Apache‑2.0), [OpenColorIO](https://opencolorio.org) и конфиги ACES (BSD‑3‑Clause), Khronos PBR Neutral (Apache‑2.0) — см. [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Лицензия

Бесплатно по [лицензии HDRI kit](LICENSE) — все права защищены, исходный код не публикуется. Сторонние компоненты: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

<sub>From Russia with love ♥</sub>
