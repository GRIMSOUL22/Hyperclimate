# Hyperclimate Final — Reference Design + Original Feature Set

React + FastAPI redesign based on the supplied Hyperclimate Python feature set. The legacy advanced Python file is included under `legacy_reference` for audit/reference.

Includes: crop selection, weather, NASA POWER baseline, Sentinel-2 analysis when satellite dependencies/data are available, farmer-friendly satellite labels, terrain, field area/zones, crop stress, heat/dryness/pest indicators, explainable alerts and printable report.

Satellite observations are not continuous live video. NISAR/authorised ISRO products are not fabricated.

## Run backend
cd backend
python -m pip install -r requirements.txt
python -m uvicorn main:app --reload --port 8000

## Run frontend
cd frontend
npm install
npm run dev

Open the Vite URL, normally http://localhost:5173/
