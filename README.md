# Forward Inflation Curve 

Inflation curve or inflation forward curve is also called Consumer Price Index (CPI) curve that is the term structures of CPI rates is defined as the relationship between CPI and different terms. The popular indices are Euro HICPxT, UK RPI, and US CPI.

Inflation curves are used to price inflation securities and inflation derivatives, such as inflation linked bonds, inflation swaps and inflation caps/floors.

Inflation products are used to hedge inflation risk. For example, real estate companies may want to shed their exposure to inflation risk, while pension funds may want to cover their natural liabilities which are exposed to inflation.

Both investors illustrated above care about real income rather than nominal income, preferring to invest in securities guaranteeing them a real return as opposed to nominal one. The real yield on bond can be decomposed into a nominal yield and breakeven inflation yield component. The breakeven inflation gives the inflation rate that makes an investor indifferent between nominal and inflation-linked investments.

Inflation indexed bonds, also called inflation linked bonds or real return bonds, are bonds where the principal is indexed to inflation or deflation on a daily basis in terms of a reference index, such as Consumer Price Index (CPI)

nflation swaps are bilateral contracts that enable an investor or hedger to secure an inflation-protected return with respect to an inflation index. The inflation buyer (also called the inflation receiver) pays a predetermined fixed or floating rate (usually minus a spread). In return, the inflation buyer receives from the inflation seller (also called the inflation payer) inflation-linked payment(s).

The zero-coupon inflation swap has become the standard inflation derivative. For many, it is the basic building block of the inflation derivatives market. Its appeal is its simplicity and the fact that it offers investors and hedgers a wide range of possibilities that did not previously exist in the cash market. Other inflation swaps are typically portfolios of zero-coupon swaps in one way or the other. In some cases, convexity adjustment may be needed.

Inflation Curve Construction

Inflation curves can be bootstrapped from liquid inflation instruments, such as inflation indexed bonds, zero coupon swaps, or inflation swaps.

Given inflation curves, pricing inflation products become straightforward. Also one can derive breakeven yields to maturity or breakeven inflation zero rates from the inflation curves. Futhermore, he can generate breakeven inflation swap rates.

Inflation Curve Data Sample

FinPricing bootstraps inflation curve from a number of inflation instruments, such as inflation linked bonds, zero-coupon inflation swaps, and inflation swaps. Those are the most liquid inflation products at certain maturities. An inflation curve sample data is shown below:

CurveName	ValuationDate	Tenor	Value
USD_CPI	2020-11-27	7/1/2020  	259.101
USD_CPI	2020-11-27	8/1/2020  	259.918
USD_CPI	2020-11-27	9/1/2020  	260.28
USD_CPI	2020-11-27	10/1/2020 	260.6455622
USD_CPI	2020-11-27	11/1/2020 	261.0116378
USD_CPI	2020-11-27	12/1/2020 	261.3782275
USD_CPI	2020-11-27	1/1/2021  	261.7453322
USD_CPI	2020-11-27	2/1/2021  	262.1129524
USD_CPI	2020-11-27	3/1/2021  	262.4810889
USD_CPI	2020-11-27	4/1/2021  	262.8497425
USD_CPI	2020-11-27	5/1/2021  	263.2189139
USD_CPI	2020-11-27	6/1/2021  	263.5886037
USD_CPI	2020-11-27	7/1/2021  	263.9588128
USD_CPI	2020-11-27	8/1/2021  	264.3295419
USD_CPI	2020-11-27	9/1/2021  	264.7007916
USD_CPI	2020-11-27	10/1/2021 	265.0725628
USD_CPI	2020-11-27	11/1/2021 	265.4448561
USD_CPI	2020-11-27	12/1/2021 	265.8176723
USD_CPI	2020-11-27	1/1/2022  	266.1910121
…	…	…	...
USD_CPI	2020-11-27	12/1/2049	461.5005978
USD_CPI	2020-11-27	1/1/2050  	462.2967314

References:

https://finpricing.com/lib/IrBasisCurve.html


