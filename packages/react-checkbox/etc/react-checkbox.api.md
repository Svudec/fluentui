## API Report File for "@fluentui/react-checkbox"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BaseSlots } from '@fluentui/react-compose';
import { ClassFunction } from '@fluentui/react-compose';
import { ComponentWithAs } from '@fluentui/react-compose';
import { IRefObject } from '@fluentui/utilities';
import { IRenderFunction } from '@fluentui/utilities';
import { IStyle } from '@fluentui/style-utilities';
import { IStyleFunctionOrObject } from '@fluentui/utilities';
import { ISvgIconProps } from '@fluentui/react-icons-mdl2';
import { ITheme } from '@fluentui/style-utilities';
import * as React from 'react';
import { SlotProp } from '@fluentui/react-compose';
import { SlotProps } from '@fluentui/react-compose';

// @public (undocumented)
export const Checkbox: React.FunctionComponent<ICheckboxProps>;

// @public (undocumented)
export const CheckboxBase: ComponentWithAs<'div', ICheckboxProps>;

// @public
export interface ICheckbox {
    checked: boolean;
    focus: () => void;
    indeterminate: boolean;
}

// @public (undocumented)
export type ICheckboxClasses = {
    [key in keyof ICheckboxSlots]: string;
};

// @public
export interface ICheckboxProps extends React.ButtonHTMLAttributes<HTMLElement | HTMLInputElement>, React.RefAttributes<HTMLElement> {
    ariaDescribedBy?: string;
    ariaLabel?: string;
    ariaLabelledBy?: string;
    as?: React.ElementType;
    boxSide?: 'start' | 'end';
    checked?: boolean;
    checkmark?: SlotProp<ISvgIconProps>;
    className?: string;
    componentRef?: IRefObject<ICheckbox>;
    defaultChecked?: boolean;
    defaultIndeterminate?: boolean;
    disabled?: boolean;
    indeterminate?: boolean;
    inputProps?: React.ButtonHTMLAttributes<HTMLElement | HTMLButtonElement>;
    label?: SlotProp<React.HTMLAttributes<HTMLSpanElement>>;
    onChange?: (ev?: React.FormEvent<HTMLElement | HTMLInputElement>, checked?: boolean) => void;
    // @deprecated
    onRenderLabel?: IRenderFunction<ICheckboxProps>;
    required?: boolean;
    // @deprecated
    styles?: IStyleFunctionOrObject<ICheckboxStyleProps, ICheckboxStyles>;
    theme?: ITheme;
}

// @public (undocumented)
export type ICheckboxSlotProps = SlotProps<ICheckboxSlots, ICheckboxProps, React.HTMLAttributes<HTMLDivElement>>;

// @public (undocumented)
export interface ICheckboxSlots extends BaseSlots {
    // (undocumented)
    checkbox: React.ElementType;
    // (undocumented)
    checkmark: React.ElementType;
    // (undocumented)
    container: React.ElementType;
    // (undocumented)
    input: React.ElementType;
    // (undocumented)
    label: React.ElementType;
}

// @public (undocumented)
export interface ICheckboxState extends Omit<ICheckboxProps, keyof ICheckboxSlotProps>, Partial<ICheckboxSlotProps> {
    // (undocumented)
    ref: React.Ref<HTMLElement>;
}

// @public (undocumented)
export interface ICheckboxStyleProps {
    // (undocumented)
    checked?: boolean;
    // (undocumented)
    className?: string;
    // (undocumented)
    disabled?: boolean;
    // (undocumented)
    indeterminate?: boolean;
    // (undocumented)
    isUsingCustomLabelRender: boolean;
    // (undocumented)
    reversed?: boolean;
    // (undocumented)
    theme: ITheme;
}

// @public (undocumented)
export interface ICheckboxStyles {
    checkbox?: IStyle;
    checkmark?: IStyle;
    input?: IStyle;
    label?: IStyle;
    root?: IStyle;
    text?: IStyle;
}

// @public (undocumented)
export const useCheckbox: (props: ICheckboxProps, forwardedRef: React.Ref<HTMLElement>) => ICheckboxState;

// @public (undocumented)
export const useCheckboxClasses: ClassFunction[];


// (No @packageDocumentation comment for this package)

```