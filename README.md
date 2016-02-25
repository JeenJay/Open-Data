# Open Data
Открытые данные администрации Предгорного муниципального района Ставропольского края

### Пример машиночитаемого содержания паспорта набора данных (meta.json)
```json
{
	"identifier": "2618017120-subdivisions",
	"title": "Перечень структурных подразделений и подведомственных учреждений администрации Предгорного муниципального района Ставропольского края",
	"description": "Перечень структурных подразделений и подведомственных учреждений администрации Предгорного муниципального района Ставропольского края",
	"publisher": {
		"owner": "Администрация Предгорного муниципального района Ставропольского края",
		"responsible": "Усс Дмитрий Васильевич",
		"phone": "+78796150664",
		"email": "it-apmr@yandex.ru"
	},
	"updating": "По мере изменений",
	"data": {
		"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/data.json",
		"format": "json",
		"created": "2014-06-16",
		"modified": {
			"date": "2015-06-05",
			"content": "Добавлена информация о должностях руководителей"
		},
		"previous": [{
			"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/data.json"
		},{
			"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/data.json"
		},{
			"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/data.json"
		},{
			"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/data.json"
		}]
	},
	"structure": {
		"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/strucrure.json",
		"format": "json",
		"created": "2014-06-16",
		"modified": {
			"date": "2015-06-05",
			"content": "Добавлено поле должность руководителя"
		},
		"previous": [{
			"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/strucrure.json"
		},{
			"source": "http://opendata.predgor-ray.ru/2618017120-subdivisions/strucrure.json"
		}]
	},
	"keywords": "структурные подразделения, отделы, управления",
	"stavdart": {
		"version": "3.0",
		"url": "http://opendata.gosmonitor.ru/standard/3.0"
	}
}
```