python-stdnum
=============

A Python module to parse, validate and reformat standard numbers and codes
in different formats. It contains a large collection of number formats.

Basically any number or code that has some validation mechanism available
or some common formatting is eligible for inclusion in this library.

https://arthurdejong.org/python-stdnum/


Available formats
-----------------

Currently this package supports the following formats:

 * NRT (Número de Registre Tributari, Andorra tax number)
 * NIPT (Numri i Identifikimit për Personin e Tatueshëm, Albanian VAT number)
 * CBU (Clave Bancaria Uniforme, Argentine bank account number)
 * CUIT (Código Único de Identificación Tributaria, Argentinian tax number)
 * DNI (Documento Nacional de Identidad, Argentinian national identity nr.)
 * Austrian Company Register Numbers
 * Postleitzahl (Austrian postal code)
 * Abgabenkontonummer (Austrian tax identification number)
 * UID (Umsatzsteuer-Identifikationsnummer, Austrian VAT number)
 * VNR, SVNR, VSNR (Versicherungsnummer, Austrian social security number)
 * ABN (Australian Business Number)
 * ACN (Australian Company Number)
 * TFN (Australian Tax File Number)
 * Belgian IBAN (International Bank Account Number)
 * BTW, TVA, NWSt, ondernemingsnummer (Belgian enterprise number)
 * EGN (ЕГН, Единен граждански номер, Bulgarian personal identity codes)
 * PNF (ЛНЧ, Личен номер на чужденец, Bulgarian number of a foreigner)
 * VAT (Идентификационен номер по ДДС, Bulgarian VAT number)
 * BIC (ISO 9362 Business identifier codes)
 * Bitcoin address
 * CNPJ (Cadastro Nacional da Pessoa Jurídica, Brazilian company identifier)
 * CPF (Cadastro de Pessoas Físicas, Brazilian national identifier)
 * УНП, UNP (Учетный номер плательщика, the Belarus VAT number)
 * BN (Canadian Business Number)
 * SIN (Canadian Social Insurance Number)
 * CAS RN (Chemical Abstracts Service Registry Number)
 * ESR, ISR, QR-reference (reference number on Swiss payment slips)
 * Swiss social security number ("Sozialversicherungsnummer")
 * UID (Unternehmens-Identifikationsnummer, Swiss business identifier)
 * VAT, MWST, TVA, IVA, TPV (Mehrwertsteuernummer, the Swiss VAT number)
 * RUT (Rol Único Tributario, Chilean national tax number)
 * RIC No. (Chinese Resident Identity Card Number)
 * USCC (Unified Social Credit Code, 统一社会信用代码, China tax number)
 * NIT (Número De Identificación Tributaria, Colombian identity code)
 * CPF (Cédula de Persona Física, Costa Rica physical person ID number)
 * CPJ (Cédula de Persona Jurídica, Costa Rica tax number)
 * CR (Cédula de Residencia, Costa Rica foreigners ID number)
 * NI (Número de identidad, Cuban identity card numbers)
 * CUSIP number (financial security identification number)
 * Αριθμός Εγγραφής Φ.Π.Α. (Cypriot VAT number)
 * DIČ (Daňové identifikační číslo, Czech VAT number)
 * RČ (Rodné číslo, the Czech birth number)
 * Handelsregisternummer (German company register number)
 * IdNr (Steuerliche Identifikationsnummer, German personal tax number)
 * St.-Nr. (Steuernummer, German tax number)
 * Ust ID Nr. (Umsatzsteur Identifikationnummer, German VAT number)
 * Wertpapierkennnummer (German securities identification code)
 * CPR (personnummer, the Danish citizen number)
 * CVR (Momsregistreringsnummer, Danish VAT number)
 * Cedula (Dominican Republic national identification number)
 * NCF (Números de Comprobante Fiscal, Dominican Republic receipt number)
 * RNC (Registro Nacional del Contribuyente, Dominican Republic tax number)
 * EAN (International Article Number)
 * CI (Cédula de identidad, Ecuadorian personal identity code)
 * RUC (Registro Único de Contribuyentes, Ecuadorian company tax number)
 * Isikukood (Estonian Personcal ID number)
 * KMKR (Käibemaksukohuslase, Estonian VAT number)
 * Registrikood (Estonian organisation registration code)
 * CCC (Código Cuenta Corriente, Spanish Bank Account Code)
 * CIF (Código de Identificación Fiscal, Spanish company tax number)
 * CUPS (Código Unificado de Punto de Suministro, Spanish meter point number)
 * DNI (Documento Nacional de Identidad, Spanish personal identity codes)
 * Spanish IBAN (International Bank Account Number)
 * NIE (Número de Identificación de Extranjero, Spanish foreigner number)
 * NIF (Número de Identificación Fiscal, Spanish VAT number)
 * Referencia Catastral (Spanish real estate property id)
 * SEPA Identifier of the Creditor (AT-02)
 * Euro banknote serial numbers
 * EIC (European Energy Identification Code)
 * NACE (classification for businesses in the European Union)
 * VAT (European Union VAT number)
 * ALV nro (Arvonlisäveronumero, Finnish VAT number)
 * Finnish Association Identifier
 * HETU (Henkilötunnus, Finnish personal identity code)
 * Veronumero (Finnish individual tax number)
 * Y-tunnus (Finnish business identifier)
 * FIGI (Financial Instrument Global Identifier)
 * NIF (Numéro d'Immatriculation Fiscale, French tax identification number)
 * NIR (French personal identification number)
 * SIREN (a French company identification number)
 * SIRET (a French company establishment identification number)
 * n° TVA (taxe sur la valeur ajoutée, French VAT number)
 * NHS (United Kingdom National Health Service patient identifier)
 * SEDOL number (Stock Exchange Daily Official List number)
 * UPN (English Unique Pupil Number)
 * UTR (United Kingdom Unique Taxpayer Reference)
 * VAT (United Kingdom (and Isle of Man) VAT registration number)
 * AMKA (Αριθμός Μητρώου Κοινωνικής Ασφάλισης, Greek social security number)
 * FPA, ΦΠΑ, ΑΦΜ (Αριθμός Φορολογικού Μητρώου, the Greek VAT number)
 * GRid (Global Release Identifier)
 * GS1-128 (Standard to encode product information in Code 128 barcodes)
 * NIT (Número de Identificación Tributaria, Guatemala tax number)
 * OIB (Osobni identifikacijski broj, Croatian identification number)
 * ANUM (Közösségi adószám, Hungarian VAT number)
 * IBAN (International Bank Account Number)
 * NPWP (Nomor Pokok Wajib Pajak, Indonesian VAT Number)
 * PPS No (Personal Public Service Number, Irish personal number)
 * VAT (Irish tax reference number)
 * Company Number (מספר חברה, or short ח.פ. Israeli company number)
 * Identity Number (Mispar Zehut, מספר זהות, Israeli identity number)
 * IMEI (International Mobile Equipment Identity)
 * IMO number (International Maritime Organization number)
 * IMSI (International Mobile Subscriber Identity)
 * Aadhaar (Indian personal identity number)
 * EPIC (Electoral Photo Identity Card, Indian Voter ID)
 * GSTIN (Goods and Services Tax identification number, Indian VAT number)
 * PAN (Permanent Account Number, Indian income tax identifier)
 * Kennitala (Icelandic personal and organisation identity code)
 * VSK number (Virðisaukaskattsnúmer, Icelandic VAT number)
 * ISAN (International Standard Audiovisual Number)
 * ISBN (International Standard Book Number)
 * ISIL (International Standard Identifier for Libraries)
 * ISIN (International Securities Identification Number)
 * ISMN (International Standard Music Number)
 * ISO 11649 (Structured Creditor Reference)
 * ISO 6346 (International standard for container identification)
 * ISRC (International Standard Recording Code)
 * ISSN (International Standard Serial Number)
 * AIC (Italian code for identification of drugs)
 * Codice Fiscale (Italian tax code for individuals)
 * Partita IVA (Italian VAT number)
 * CN (法人番号, hōjin bangō, Japanese Corporate Number)
 * BRN (사업자 등록 번호, South Korea Business Registration Number)
 * RRN (South Korean resident registration number)
 * LEI (Legal Entity Identifier)
 * PEID (Liechtenstein tax code for individuals and entities)
 * Asmens kodas (Lithuanian, personal numbers)
 * PVM (Pridėtinės vertės mokestis mokėtojo kodas, Lithuanian VAT number)
 * TVA (taxe sur la valeur ajoutée, Luxembourgian VAT number)
 * PVN (Pievienotās vērtības nodokļa, Latvian VAT number)
 * MAC address (Media Access Control address)
 * n° TVA (taxe sur la valeur ajoutée, Monacan VAT number)
 * IDNO (Moldavian company identification number)
 * Montenegro IBAN (International Bank Account Number)
 * MEID (Mobile Equipment Identifier)
 * VAT (Maltese VAT number)
 * ID number (Mauritian national identifier)
 * CURP (Clave Única de Registro de Población, Mexican personal ID)
 * RFC (Registro Federal de Contribuyentes, Mexican tax number)
 * NRIC No. (Malaysian National Registration Identity Card Number)
 * BRIN number (the Dutch school identification number)
 * BSN (Burgerservicenummer, the Dutch citizen identification number)
 * Btw-identificatienummer (Omzetbelastingnummer, the Dutch VAT number)
 * Onderwijsnummer (the Dutch student identification number)
 * Postcode (the Dutch postal code)
 * Fødselsnummer (Norwegian birth number, the national identity number)
 * Norwegian IBAN (International Bank Account Number)
 * Konto nr. (Norwegian bank account number)
 * MVA (Merverdiavgift, Norwegian VAT number)
 * Orgnr (Organisasjonsnummer, Norwegian organisation number)
 * New Zealand bank account number
 * IRD number (New Zealand Inland Revenue Department (Te Tari Tāke) number)
 * CUI (Cédula Única de Identidad, Peruvian identity number)
 * RUC (Registro Único de Contribuyentes, Peruvian company tax number)
 * NIP (Numer Identyfikacji Podatkowej, Polish VAT number)
 * PESEL (Polish national identification number)
 * REGON (Rejestr Gospodarki Narodowej, Polish register of economic units)
 * CC (Número de Cartão de Cidadão, Portuguese Identity number)
 * NIF (Número de identificação fiscal, Portuguese VAT number)
 * RUC number (Registro Único de Contribuyentes, Paraguay tax number)
 * CF (Cod de înregistrare în scopuri de TVA, Romanian VAT number)
 * CNP (Cod Numeric Personal, Romanian Numerical Personal Code)
 * CUI or CIF (Codul Unic de Înregistrare, Romanian company identifier)
 * ONRC (Ordine din Registrul Comerţului, Romanian Trade Register identifier)
 * PIB (Poreski Identifikacioni Broj, Serbian tax identification number)
 * ИНН (Идентификационный номер налогоплательщика, Russian tax identifier)
 * Orgnr (Organisationsnummer, Swedish company number)
 * Personnummer (Swedish personal identity number)
 * Postcode (the Swedish postal code)
 * VAT (Moms, Mervärdesskatt, Swedish VAT number)
 * UEN (Singapore's Unique Entity Number)
 * ID za DDV (Davčna številka, Slovenian VAT number)
 * IČ DPH (IČ pre daň z pridanej hodnoty, Slovak VAT number)
 * RČ (Rodné číslo, the Slovak birth number)
 * COE (Codice operatore economico, San Marino national tax number)
 * NIT (Número de Identificación Tributaria, El Salvador tax number)
 * MOA (Thailand Memorandum of Association Number)
 * PIN (Thailand Personal Identification Number)
 * TIN (Thailand Taxpayer Identification Number)
 * T.C. Kimlik No. (Turkish personal identification number)
 * VKN (Vergi Kimlik Numarası, Turkish tax identification number)
 * UBN (Unified Business Number, 統一編號, Taiwanese tax number)
 * ЄДРПОУ, EDRPOU (Identifier for enterprises and organizations in Ukraine)
 * РНОКПП, RNTRC (Individual taxpayer registration number in Ukraine)
 * ATIN (U.S. Adoption Taxpayer Identification Number)
 * EIN (U.S. Employer Identification Number)
 * ITIN (U.S. Individual Taxpayer Identification Number)
 * PTIN (U.S. Preparer Tax Identification Number)
 * RTN (Routing transport number)
 * SSN (U.S. Social Security Number)
 * TIN (U.S. Taxpayer Identification Number)
 * RUT (Registro Único Tributario, Uruguay tax number)
 * VATIN (International value added tax identification number)
 * RIF (Registro de Identificación Fiscal, Venezuelan VAT number)
 * MST (Mã số thuế, Vietnam tax number)
 * ID number (South African Identity Document number)
 * TIN (South African Tax Identification Number)
 * EMŠO (Slovenian Unique Master Citizen Number)

Furthermore a number of generic check digit algorithms are available:

 * the Verhoeff algorithm
 * the Damm algorithm
 * the Luhn and Luhn mod N algorithms
 * some algorithms described in ISO/IEC 7064: Mod 11, 2, Mod 37, 2,
   Mod 97, 10, Mod 11, 10 and Mod 37, 36

Basically any number or code that has some validation mechanism available
or some common formatting is eligible for inclusion into this library.

These modules generally do not provide background information on the meaning
and use of the specified numbers, only parsing and handling functions.

Interface
---------

All modules implement a common interface. For example for ISBN validation:

    >>> from stdnum import isbn
    >>> isbn.validate('978-9024538270')
    '9789024538270'
    >>> isbn.validate('978-9024538271')
    Traceback (most recent call last):
        ...
    InvalidChecksum: ...

Most of these modules implement the following functions:

 * `validate()`
    validate the correctness of the passed number and return a compact
    representation of the number invalid numbers are rejected with one of the
    exceptions from the stdnum.exceptions module
 * `compact()`
   return a compact representation of the number or code this function
   generally does not do validation but may raise exceptions for wildly
   incorrect numbers
 * `format()`
   return a formatted version of the number in the preferred format this
   function generally expects to be passed a valid number or code

Apart from the above, the module may add extra parsing, validation or
conversion functions.

Requirements
------------

The modules should not require any external Python modules and should be pure
Python. The modules are developed and tested with Python 2.7 and 3.6 but may
also work with older versions of Python.

Copyright
---------

Copyright (C) 2010-2021 Arthur de Jong and others

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA
02110-1301 USA

Feedback and bug reports
------------------------

If you have any questions regarding python-stdnum, would like to report a bug
or request addition of a format please send an email to
<python-stdnum-users@lists.arthurdejong.org>
Patches and code contributions are more than welcome.
